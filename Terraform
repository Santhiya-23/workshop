provider "aws" {
    region = "us-east-2"  
}

resource "aws_instance" "foo" {
  ami           = "ami-0f5ee92e2d63afc18" # us-east-2
  instance_type = "t2.micro"  
   tags = {
      Name = "TF-Server"
  }
}
