# Ojos Project's Resources Repository

This is a collection of resources found and organized in a single JSON file for
developers to use in hospice-related software. These resources are for hospice
patients and caregivers to use.

## Usage

To use this file, you can call a GET request to the `request.json` file. You
must use
[this link](https://raw.githubusercontent.com/ojosproject/resources/release/resources.json)
to fetch the resources from the approved `release` branch.

## Support

If you notice an issue with any of these resources, please open an Issue in this
repository.

## Contributing

You have a few options for contributing to this repository:

- Add the resource to the JSON file directly and open a PR
- You may open an Issue with the "Add Resource" label and wait for us to add it
  (coming soon...)

### JSON File Structure

The JSON file is an array of Resource objects. A Resource object looks like
this:

```json
{
    "label": "Resource Label",
    "description": "A long, multi-line description about the resource.",
    "url": "A link for people to get more information.",
    "added_by": "The person or organization who added that information.",
    "type": "The type of resource. Financial? Mental health? Legal?"
}
```

## License

[MIT](https://choosealicense.com/licenses/mit/)
