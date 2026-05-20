# `step-security/dsanders11-project-actions/get-project`

Get a GitHub project

## Inputs

| Name             | Description                                                                                                        | Required | Default                          |
| ---------------- | ------------------------------------------------------------------------------------------------------------------ | -------- | -------------------------------- |
| `token`          | A GitHub access token - either a classic PAT or a GitHub app installation token.                                   | Yes      |                                  |
| `owner`          | The owner of the project - either an organization or a user. If not provided, it defaults to the repository owner. | No       | `${{ github.repository_owner }}` |
| `project-number` | The project number from the project's URL.                                                                         | Yes      |                                  |

## Outputs

| Name          | Description                            |
| ------------- | -------------------------------------- |
| `id`          | The global ID for the project.         |
| `closed`      | The closed state of the project.       |
| `field-count` | The number of fields on the project.   |
| `item-count`  | The number of items in the project.    |
| `public`      | The public visibility of the project.  |
| `readme`      | The readme description of the project. |
| `description` | The short description of the project.  |
| `title`       | The title of the project.              |
| `url`         | The URL of the project.                |

## License

MIT
