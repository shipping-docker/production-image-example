# Production Image Example

How I create production images, in particular for Laravel apps.

There are two parts:

1. The base image, which has things that don't change much (php, nginx, fpm, and potential configurations)
2. The final production image, which just adds in new code, gets dependencies, build static assets, and is complete. This uses a multi-stage build process.

More details are in the [Shipping Docker](https://shippingdocker.com) course!

