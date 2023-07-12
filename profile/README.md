# ADH-Partnership

The Anchorage, Denver and Honolulu Partnership is a group of [VATUSA](https://www.vatusa.net) facilities combining resources to build a versatile web stack.

## Container Images

Container images are pushed to [Docker Hub](https://hub.docker.com/u/adhp).  As images begin to be deployed, they will be signed.

Signature verification can be performed via:

```bash
> cosign verify --key https://raw.githubusercontent.com/adh-partnership/.github/main/cosign.pub (image):(tag)
```

For more information, see the [Cosign Documentation](https://docs.sigstore.dev/cosign/overview).

Branches generating signed images (image tags will be [main/dev]-[commit hash]):
- [x] adhp/api:dev
- [x] adhp/api:main
- [x] adhp/auth:main
- [x] adhp/frontend:dev
- [x] adhp/frontend:main
- [ ] adhp/discord:[zdv/zan/hcf]
