# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...


http://awspolicygen.s3.amazonaws.com/policygen.html

{
  "Id": "Policy1564834554793",
  "Version": "2012-10-17",
  "Statement": [
    {
      "Sid": "Stmt1564834526924",
      "Action": [
        "s3:GetObject"
      ],
      "Effect": "Allow",
      "Resource": "arn:aws:s3:::bucket-name-goes-here/*",
      "Principal": {
          "AWS": [
            "*"
          ]
      }
    }
  ]
}

TODO : is_admin isn't set when a user signs up
TODO : stripe payments arent actually working
TODO : S3 uploads now error
