# Create a Bucket<a name="S3 buket creation"></a>

sign into Amazon console
1)Amazon services --> 2)S3 --> 3)click on creat bucket --> 4) Bucket Name*  --> 5)Region --> 6)click on create --> 7) Bucket creation done

4) Bucket Name
	• Bucket names must be unique across all existing bucket names in Amazon S3.
	• Bucket names must comply with DNS naming conventions.
	• Bucket names must be at least 3 and no more than 63 characters long.
	• Bucket names must not contain uppercase characters or underscores.
	• Bucket names must start with a lowercase letter or number.
	• Bucket names must be a series of one or more labels. Adjacent labels are separated by a single period (.). Bucket names can contain lowercase letters, numbers, and hyphens. Each label must start and end with a lowercase letter or a number.
	• Bucket names must not be formatted as an IP address (for example, 192.168.5.4).
When you use virtual hosted–style buckets with Secure Sockets Layer (SSL), the SSL wildcard certificate only matches buckets that don't contain periods. To work around this, use HTTP or write your own certificate verification logic. We recommend that you do not use periods (".") in bucket names when using virtual hosted–style buckets.

** Remember**
Pricing for S3 bucket:
(https://aws.amazon.com/s3/pricing/
user will not be charged for creating s3 bucket. user will be charged for in/out transfer of files and storage.





