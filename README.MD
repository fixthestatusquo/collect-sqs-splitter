
Receives actions from SQS, passes them to other SQS queues (identity and some to thank you)

# Configuration

- `DOWNLOAD_ACTION_TYPE` - Proca action type which means thank you email with postcard must be send to user. Currently we use value "register"
- `IDENTITY_QUEUE` - queue of identity lambda
- `THANKYOU_QUEUE` - queue of thank you sender lambda
