# AHN Virtual Zarr

Material on how to build and consume virtual Zarr stores of AHN-derived datasets.

## Running the notebooks

Clone and access this repository:

```shell
git clone git@github.com:CLOUD-NES/ahn-virtual-zarr.git
cd ahn-virtual-zarr
```

Create a virtual environment with all required dependencies:

```shell
uv sync
```

## S3 configuration

S3 access to the SURF object store requires the following configuration:

```shell
export AWS_S3_ENDPOINT="objectstore.surf.nl"
export AWS_ENDPOINT_URL="https://objectstore.surf.nl"
export AWS_REGION="default"
export AWS_ACCESS_KEY_ID="<YOUR-ACCESS-KEY-ID>"
export AWS_SECRET_ACCESS_KEY="<YOUR-SECRET-ACCESS-KEY>"
```