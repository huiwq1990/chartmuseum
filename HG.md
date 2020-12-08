
--storage local --storage-local-rootdir /tmp --depth 1 --depth-dynamic true


--storage=amazon --storage-amazon-bucket=chart-hub --storage-amazon-region=us-east-1 --storage-amazon-endpoint=http://114.67.221.58:9000

    AWS_ACCESS_KEY_ID=admin
    AWS_SECRET_ACCESS_KEY=admin@123
    STORAGE=amazon
    STORAGE_AMAZON_BUCKET=chart-hub
    STORAGE_AMAZON_REGION: us-east-1
    STORAGE_AMAZON_ENDPOINT=http://114.67.221.58:9000



export AWS_ACCESS_KEY_ID="admin"
export AWS_SECRET_ACCESS_KEY="admin@123"
bin/linux --debug --port=8080 \
  --storage="amazon" \
  --storage-amazon-bucket="chart-hub" \
  --storage-amazon-prefix="" \
  --storage-amazon-region="us-east-1" \
  --storage-amazon-endpoint="http://114.67.221.58:9000"

