# OVERVIEW OF AGENTIC AI 
- LangGraph is a library for building stateful, multi-actor applications with LLMs, used to create agent and multi-agent workflows. Check out an introductory tutorial here.

- LangGraph is inspired by Pregel and Apache Beam. The public interface draws inspiration from NetworkX. LangGraph is built by LangChain Inc, the creators of LangChain, but can be used without LangChain.

# Why use LangGraph?
- LangGraph provides fine-grained control over both the flow and state of your agent applications. It implements a central persistence layer, enabling features that are common to most agent architectures:

# Memory: LangGraph persists arbitrary aspects of your application's state, supporting memory of conversations and other updates within and across user interactions;
Human-in-the-loop: Because state is checkpointed, execution can be interrupted and resumed, allowing for decisions, validation, and corrections at key stages via human input.
Standardizing these components allows individuals and teams to focus on the behavior of their agent, instead of its supporting infrastructure.

- Through LangGraph Platform, LangGraph also provides tooling for the development, deployment, debugging, and monitoring of your applications.

- LangGraph integrates seamlessly with LangChain and LangSmith (but does not require them).

- To learn more about LangGraph, check out our first LangChain Academy course, Introduction to LangGraph, available for free here.

# LangGraph Platform
LangGraph Platform is infrastructure for deploying LangGraph agents. It is a commercial solution for deploying agentic applications to production, built on the open-source LangGraph framework. The LangGraph Platform consists of several components that work together to support the development, deployment, debugging, and monitoring of LangGraph applications: LangGraph Server (APIs), LangGraph SDKs (clients for the APIs), LangGraph CLI (command line tool for building the server), and LangGraph Studio (UI/debugger).


