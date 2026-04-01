# Terraform S3 Backend Lab

## When is the state file created?

The state file is created when `terraform apply` is executed. It is not created during `terraform plan` because no real changes are made at that stage.

## When is the lock file present?

The lock file is present during Terraform operations such as `terraform plan` or `terraform apply`. It exists while Terraform is actively working with the state.

## Is the lock file always in the bucket after it is created?

No, the lock file is temporary. It only exists while Terraform is running and is removed once the operation is complete.

## Screenshots

### State File

![State File](state-file.png)

### Lock File

![Lock File](lock-file.png)
