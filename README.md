# OHA Assets

Public image hosting for Oakland Heritage Alliance email campaigns and social media posts.

## Usage

Images in this repo are referenced by their raw GitHub URL:

```
https://raw.githubusercontent.com/oaklandheritage/assets/main/images/<filename>
```

## Structure

```
images/
└── <slug>/          # one folder per campaign, e.g. three-petitions-protect-landmarks/
    └── *.jpg / *.png
```

## Adding images

1. Copy image files into `images/<campaign-slug>/`
2. Commit and push to `main`
3. Use the raw URL in the draft's `Newsletter JSON` `image` field
