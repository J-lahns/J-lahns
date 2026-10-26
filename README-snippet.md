# Signature engineering animation — installation

## 1. Upload the SVG

In the `J-lahns/J-lahns` repository, select the `main` branch, choose **Add file → Upload files**, and upload `assets/signature-process.svg` so the path in the repository is exactly:

`assets/signature-process.svg`

If uploading through GitHub's website, open the repository's `assets` folder first and upload the file there. Commit the file to `main` with the message `Add signature engineering animation`.

## 2. Embed it in README.md

Add this block after the `The blueprint` introduction and its bullet list, immediately before `## 🧩 Selected projects`:

```html
<p align="center">
  <img src="assets/signature-process.svg" alt="J-lahns engineering loop: Idea, Build, Test, Refine, Ship and repeat." width="100%" />
</p>
```

Commit the README change with a message such as `Add animated engineering loop to profile`.

## Animation and compatibility

The artwork is a self-contained SVG using SVG's declarative SMIL animations; it does not need JavaScript, an external image service, or a new GitHub Actions workflow. GitHub renders SVGs in README images and supports common SMIL animations, though third-party mirrors or previews may show only a still frame.
