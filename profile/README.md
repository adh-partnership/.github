# ADH-Partnership

The Anchorage, Denver and Honolulu Partnership is a group of [VATUSA](https://www.vatusa.net) facilities combining resources to build a versatile web stack.

## Container Images

Container images are pushed to Docker Hub.  As images begin to be deployed, they will be signed.

Signature verification can be performed via:

```bash
> cosign verify --key https://raw.githubusercontent.com/adh-partnership/.github/main/cosign.pub (image):(tag)
```

For more information, see the (https://docs.sigstore.dev/cosign)[Cosign Documentation].

Images currently signed:
- [x] adhp/api:dev
- [ ] adhp/api:main
- [ ] adhp/frontend:dev
- [ ] adhp/frontend:main
