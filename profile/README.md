## getapp

### Introduction

**getapp** is an open-source project that reimagines the distribution of DevOps tools to edge devices. While most tools, such as ArgoCD, rely on a push method for distribution, **getapp** introduces a novel pull-based approach based on discovery.

### How it Works

1. **Discovery**: Edge devices initiate a discovery call to determine if they need an update.
2. **Custom Offering**: A custom offering is created per the edge device's request, ensuring tailored updates.
3. **Delivery**: Upon customer interaction, the system queries and prepares the installable artifacts.
4. **Deploy**: The system then deploys the artifacts on the edge devices, ensuring seamless updates.

### Benefits

- **Efficient Updates**: By only updating when necessary, **getapp** reduces unnecessary bandwidth and resource usage.
- **Customization**: Each edge device receives a custom offering based on its specific requirements.
- **Seamless Deployment**: Updates are deployed automatically, streamlining the update process for edge devices.

### Getting Started

To get started with **getapp**, refer to the [documentation](link-to-docs) for installation and usage instructions.


<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
