# Upload OSS

Upload files to oss of aliyun

## Inputs

### `key-id`

**Required** access key ID of oss. Default `''`.

### `key-secret`

**Required** access key secret of oss. Default `''`.

### `endpoint`

**Required** endpoint of oss. Default `''`.

### `bucket`

**Required** bucket of oss. Default `''`.

### `asset-path`

**Required** file path to be uploaded. Default `''`.

### `target-path`

**Required** path where the oss object is stored. Default `''`.

## Example usage

```yaml
uses: vesoft-inc/upload-oss
with:
    key-id: ${{ secrets.OSS_ID }}
    key-secret: ${{ secrets.OSS_SECRET }}
    endpoint: ${{ secrets.OSS_ENDPOINT }}
    bucket: oss-bucket
    asset-path: /path/to/assets
    target-path: /path/to/target/files
```
