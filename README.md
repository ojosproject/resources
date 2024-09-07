# Ojos Project's Resources Repository

![Ojos Project header](https://ojosproject.org/images/header.png)

## Table of Contents

- [Ojos Project's Resources Repository](#ojos-projects-resources-repository)
  - [Table of Contents](#table-of-contents)
  - [Description](#description)
  - [Usage](#usage)
  - [Support](#support)
  - [Contributing](#contributing)
    - [JSON File Structure](#json-file-structure)
  - [License](#license)

## Description

This is a collection of resources found and organized in a single JSON file for
developers to use in hospice-related software. These resources are for hospice
patients and caregivers to use.

## Usage

To use this file, you can call a GET request to the `request.json` file. You
must use
[this link](https://raw.githubusercontent.com/ojosproject/resources/main/resources.json)
to fetch the resources from the `main` branch.

## Support

If you notice an issue with any of these resources, please open an Issue in this
repository.

## Contributing

You have a few options for contributing to this repository:

- Add the resource to the JSON file directly and open a PR
- You may [open an Issue](https://github.com/ojosproject/resources/issues/new/choose/)
  with the "Add Resource" label and wait for us to add it

### JSON File Structure

The JSON file is an array of Resource objects. A Resource object looks like
this:

```json
{
    "label": "",
    "description": "",
    "url": "",
    "organization": "",
    "category": "",
    "last_updated": 0
}
```

| Key            | Type     | Description                                                 |
| -------------- | -------- | ----------------------------------------------------------- |
| `label`        | `string` | A label for the resource. Think of it as a title.           |
| `description`  | `string` | A long, multi-line description about the resource.          |
| `url`          | `string` | A link for people to get more information.                  |
| `organization` | `string` | The person or organization who provides the resource.       |
| `category`     | `string` | The kind of resource. Options include: `FINANCIAL`, `LEGAL` |
| `last_updated` | `number` | The Unix timestamp of when the resource was modified.       |

## License

[MIT](https://choosealicense.com/licenses/mit/)
