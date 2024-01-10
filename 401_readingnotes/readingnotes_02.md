# Reading notes 2

**Explain the levels of abstraction in AWS to someone without a technical background:**
   - AWS has different levels of services or tools. There are basic tools (instances), more specialized ones (containers), a fast service for specific tasks (AWS Lambda), and a fully managed service doing everything automatically (AWS Fargate).

**What are the control plane and data plane responsible for in container abstraction?**
   - In container abstraction, the control plane manages and decides on container-related operations. The data plane executes and delivers those operations which ensures containers have the necessary resources.

**Where does AWS Lambda fall in the layers of abstraction and what makes it so special?**
   - AWS Lambda operates at a higher level of abstraction, meaning it simplifies the way we handle computing tasks. It allows us to focus on specific functions without getting into the technical details of managing servers or complex resources.
   - It provides a serverless computing environment where users can run individual functions without managing underlying infrastructure. It provides efficient and specific function execution without the need for server management.

## source: https://aws.amazon.com/blogs/architecture/compute-abstractions-on-aws-a-visual-story/