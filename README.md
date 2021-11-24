# Image Finder

## Brief
We would like to build a Flutter application using Dart that displays images.

A basic App would have the following functionalities:
- Fetch data from the NASA external API: https://images-api.nasa.gov/search?q=moon
- Transform the data
- Display on the page in a grid that contain 2 images per row

Here is an excerpt from https://images-api.nasa.gov/search?q=moon:

```
{
  "collection": {
    "href": "https://images-api.nasa.gov/search?q=moon",
    "version": "1.0",
    "items": [
      {
        "href": "https://images-assets.nasa.gov/image/PIA12235/collection.json",
        "data": [ ... ],
        "links": [
          {
            "href": "https://images-assets.nasa.gov/image/PIA12235/PIA12235~thumb.jpg",
            "render": "image",
            "rel": "preview"
          }
        ]
      }
    ]
  }
}
```

## Extensions
We could plan to extend the service by introducing:
- Test coverage or implementing directly a TDD approach
- Content styling

## Notes

You are free to code and run the application using any IDE/text editor of your choice.
You can search the web for information as you'd do in normal work day or ask your interviewers for help and collaboration.
