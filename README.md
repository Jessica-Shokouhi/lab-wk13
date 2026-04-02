# 4640 Week 13 lab

### Completed by Jessica, Cole, Kyle

## When is the state file created?

The state file is created when `terraform apply` is executed. It is not created during `terraform plan` because no real changes are made at that stage.

## When is the lock file present?

The lock file is present during Terraform operations such as `terraform plan` or `terraform apply`. It exists while Terraform is actively working with the state.

## Is the lock file always in the bucket after it is created?

No, the lock file is temporary. It only exists while Terraform is running and is removed once the operation is complete.

## Screenshots

### State File

<img width="2878" height="1614" alt="state-file" src="https://github.com/user-attachments/assets/ce3c4716-1340-4bd2-afe9-6a502130ddda" />

### Lock File

<img width="2880" height="1604" alt="lock-file" src="https://github.com/user-attachments/assets/051f30d5-282c-44cd-bf27-a6181f1c7c51" />
