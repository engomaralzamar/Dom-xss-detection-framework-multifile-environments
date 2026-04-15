🔍 Project Overview: Framework for DOM-based XSS Detection This repository contains the implementation of a specialized framework designed to identify and track DOM-based Cross-Site Scripting (XSS) vulnerabilities in complex, multi-file environments.

🛠️ Enhanced Static Analysis & Integration The integration layer enhances existing tools to support deep-context scanning:

Custom Semgrep Rules: Optimized for specific sinks.

AST-based Taint Tracking: Using nikic/php-parser to build Abstract Syntax Trees, optimized for specific source Cross-File Mapping: Scripts that link backend data flow directly to frontend rendering components.

📂 Repository Structure /link source with sink.rar: Scripts for integrating the parser with the scanning engine.

/Semgrep : Enhanced Semgrep patterns for DOM-XSS detection.

/php-parser: Logic for AST generation and data-flow tracing.
