<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/logo-dark.svg">
    <img src="assets/logo-light.svg" alt="yggy" height="56">
  </picture>
</p>

<h1 align="center">yggy SDK for Go</h1>

<p align="center">Typed client for the yggy API. Go 1.23 or newer.</p>

## Install

```bash
go get github.com/yggy-tech/yggy-sdk-go
```

## Example

List the projects your key can see:

```go
package main

import (
	"context"
	"fmt"
	"log"
	"os"

	yggy "github.com/yggy-tech/yggy-sdk-go"
)

func main() {
	cfg := yggy.NewConfiguration()
	cfg.AddDefaultHeader("x-yggy-organization-id", "acme-corp")
	client := yggy.NewAPIClient(cfg)

	ctx := context.WithValue(context.Background(), yggy.ContextAPIKeys, map[string]yggy.APIKey{
		"apiKeyAuth": {Key: os.Getenv("YGGY_API_KEY")},
	})
	res, _, err := client.ProjectsAPI.ListProjects(ctx).Execute()
	if err != nil {
		log.Fatal(err)
	}
	for _, project := range res.Projects {
		fmt.Println(project.Name)
	}
}
```

## Authenticate

Create an API key in yggy under **Developers → API keys** and keep it in an environment variable. A key that belongs to one organization needs nothing else. A personal key can see several organizations, so name the one you want in the `x-yggy-organization-id` header, by id or slug, as the example does.

See [Authentication](https://docs.yggy.tech/developers/authentication/) for key types and permissions.

## What you can call

Projects, documents (upload, status, extracted facts, download, retry), questions over a project or a whole organization, chat, entity lookup by identity, the ontology overview and graph exports. The [API reference](https://docs.yggy.tech/developers/rest/reference/) lists every operation with its parameters. For a first walkthrough, follow the [quickstart](https://docs.yggy.tech/developers/quickstart/).

## Generated code

Everything except this file is generated from the yggy OpenAPI document, so a change here is overwritten by the next sync. Report bugs or request an operation by opening an issue in this repository, or write to [support](https://yggy.tech/support).

## License

Apache-2.0. See [LICENSE](LICENSE).
