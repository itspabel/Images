# Images Repository

This repository serves as a collection of images that are uploaded here and converted for use via jsDelivr. These images are then embedded and utilized on websites or other projects.

## Purpose

- To store and manage images in a version-controlled manner.
- To leverage jsDelivr for fast and reliable CDN hosting of the images.
- To simplify embedding images in websites and projects using jsDelivr URLs.

## How to Use

1. **Upload Images**: Add your images to the repository by committing them to the desired directory.

2. **Get the jsDelivr URL**:
   - After committing the image, construct its jsDelivr URL using the following format:
     ```
     https://cdn.jsdelivr.net/gh/<GitHub_Username>/<Repo_Name>@<Branch_or_Tag>/<Path_to_Image>
     ```
   - Replace:
     - `<GitHub_Username>` with your GitHub username.
     - `<Repo_Name>` with the name of this repository (e.g., `Images`).
     - `<Branch_or_Tag>` with the branch name (e.g., `main`) or tag.
     - `<Path_to_Image>` with the relative path to the image in the repository.

   Example:
   ```
   https://cdn.jsdelivr.net/gh/itspabel/Images@main/example/image.jpg
   ```

3. **Embed in Your Website**:
   - Use the jsDelivr URL to embed the image in your website or project:
     ```html
     <img src="https://cdn.jsdelivr.net/gh/itspabel/Images@main/example/image.jpg" alt="Example Image">
     ```

## Notes

- Ensure that the repository is public if you want the images to be accessible via jsDelivr.
- You can use tags or branch names in the jsDelivr URL to reference specific versions of the images.
- For better organization, structure your images into folders based on categories or usage.

## License

Include a license for your images if applicable (e.g., [Creative Commons](https://creativecommons.org/) or another license).

## Acknowledgments

- [jsDelivr](https://www.jsdelivr.com/) for providing a fast and free CDN service.

---
