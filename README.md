# Amazon Q CLI for Ubuntu Linux

> A game-changer for AWS developers!

Amazon Q CLI is AWS's AI-powered developer tool that brings generative AI assistance directly to your terminal. It helps you build, troubleshoot, and interact with AWS services through natural language conversations.

## Installation Guide

Want to try it yourself? Here's the exact installation process:

### 1. Download the installer

```bash
curl --proto '=https' --tlsv1.2 -sSf "https://desktop-release.q.us-east-1.amazonaws.com/latest/q-x86_64-linux.zip" -o "q.zip"
```

### 2. Unzip the package

```bash
unzip q.zip
```

### 3. Run the installer

```bash
./q/install.sh
```

### 4. Add to your PATH (if not done automatically)

```bash
export PATH=$PATH:$HOME/.local/bin
```

### 5. Set up AWS credentials securely (session-only for enhanced security)

```bash
export AWS_ACCESS_KEY_ID=your_access_key_here
export AWS_SECRET_ACCESS_KEY=your_secret_key_here
export AWS_DEFAULT_REGION=your_preferred_region
```

> **Pro security tip**: Using environment exports keeps credentials in memory only for your current session - they'll disappear when you log out!

### 6. First-time login

When you first run Amazon Q CLI, you'll be prompted to authenticate with your AWS account. The tool will use the credentials you exported.

### 7. Start Amazon Q

```bash
q chat
```

### 8. Welcome experience

After authentication, you'll see a welcome message with information about Amazon Q's capabilities and how to interact with it.

### 9. Navigate the platform

Type `/help` to display all available commands and navigation options.

Key commands include:
- `/quit` - Exit Amazon Q CLI
- `/clear` - Clear the conversation history
- `/feedback` - Provide feedback on responses
- `/history` - View your conversation history

## Powerful Examples

Check out these powerful examples of what Amazon Q CLI can do:

### AWS resource management
```
"List all my EC2 instances in us-west-2 region"
```

### Code generation
```
"Write a Python Lambda function that processes S3 events"
```

### Troubleshooting
```
"Help me understand this CloudWatch error message: [your error]"
```

### Infrastructure as Code
```
"Create a CloudFormation template for a VPC with public and private subnets"
```

### Local file operations
```
"Find all Python files in my current directory that use boto3"
```

## Resources

- [Official AWS Documentation](https://docs.aws.amazon.com/amazonq/latest/cli-user-guide/what-is.html)
- [Amazon Q Developer Guide](https://docs.aws.amazon.com/amazonq/latest/qdeveloper-guide/what-is.html)
- [AWS Blog - Introducing Amazon Q CLI](https://aws.amazon.com/blogs/aws/amazon-q-developer-agent-in-preview/)
- [GitHub Repository](https://github.com/aws/aws-cli-q)

---

Amazon Q CLI combines the power of AI with direct AWS integration - all from your terminal!

**Tags**: AWS, Amazon Q, Developer Tools, Cloud Computing, AI, Ubuntu, Linux, Security
