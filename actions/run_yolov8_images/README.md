# run_yolov8_images

This Action runs the yolov8 object detector on a folder of images.

## Getting started

1. Setup a virtual environment specific to this project and install development dependencies, including the `roboto` CLI: `./scripts/setup.sh`
2. Build Docker image: `./scripts/build.sh`
3. Run Action image locally: `./scripts/run.sh <path-to-input-data-directory>`
4. Run tests: `./scripts/test.sh`
5. Deploy to Roboto Platform: `./scripts/deploy.sh`

## Action configuration file

This Roboto Action is configured in `action.json`. Refer to Roboto's latest documentation for the expected structure.
