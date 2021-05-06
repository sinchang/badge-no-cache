# badge-no-cache

## Why

If you upload an image to GitHub, the URL of the image will be modified and the content of the image will be cached, it would cause data on the badge image doesn't update immediately.

## How

Update badge url as the below format:

```
https://badge-no-cache.sinchang.workers.dev?${badge url}
```

## Who using it

if you use this approach, please let me know.

## References

- https://docs.github.com/en/github/authenticating-to-github/about-anonymized-image-urls
