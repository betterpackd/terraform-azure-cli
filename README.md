# Terraform and Azure CLI OCI image

Terraform and Azure CLI in a Container image.

## 💡 Motivation

The goal is to create a **minimalist** and **lightweight** image with these tools in order to reduce network and storage impact.

This image gives you the flexibility to be used either for development or as a base image as you see fits.

## 🔧 What's inside ?

- [Azure CLI](https://docs.microsoft.com/cli/azure/)
- [Terraform CLI](https://developer.hashicorp.com/terraform/cli/)
- [Git](https://git-scm.com/)
- [Python 3](https://www.python.org/)
- This image use a non root user with a GID and UID of 1001 to conform with docker security best practices.

## 📖 License

This project is under the [MIT](LICENSE).
