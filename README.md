# badge-no-cache

## Why

If you add an image to GitHub, the URL of the image will be modified and the content of the image will be cached, it would cause data on the badge image doesn't update immediately.

## How

Update badge url as the below format:

```
https://badge-no-cache.sinchang.workers.dev?${badge url}
```

## Example

#### Default

<a href="https://www.producthunt.com/posts/slidev?utm_source=badge-featured&utm_medium=badge&utm_souce=badge-slidev" target="_blank"><img src="https://api.producthunt.com/widgets/embed-image/v1/featured.svg?post_id=294908&theme=dark" alt="Slidev - Presentation Slides for Developers | Product Hunt" width="200"/></a>

#### Using `badge-no-cache`

<a href="https://www.producthunt.com/posts/slidev?utm_source=badge-featured&utm_medium=badge&utm_souce=badge-slidev" target="_blank"><img src="https://badge-no-cache.sinchang.workers.dev?https://api.producthunt.com/widgets/embed-image/v1/featured.svg?post_id=294908&theme=dark" alt="Slidev - Presentation Slides for Developers | Product Hunt" width="200"/></a>

## Who using it

If you use this approach, please let me know.

## References

- https://docs.github.com/en/github/authenticating-to-github/about-anonymized-image-urls
