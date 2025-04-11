# **📂 OmniCode-Assembler/** *(Root of the Repository)*  

- 📜 **README.md** *(Project Overview, Setup Instructions, Execution Notes)*  
- 📜 **LICENSE.md** *(CreativeWorkzStudio LLC Licensing Terms)*  
- 📜 **.gitignore** *(Ensures unnecessary files are not tracked in GitHub)*  
- 📜 **file-structure-basic.md** *(Defines and documents OmniCode’s directory layout and purpose)*  

---

## **📂 config/** *(Manages structured execution configuration for OmniCode)*  

- 📂 **schema/** *(Defines structured execution rules and validation schema)*  
  - 📜 **omnicode-schema-instruction-set.json** *(Defines OmniCode’s instruction schema and validation rules)*  

- 📂 **json/** *(Stores dynamic execution data for OmniCode instruction sets)*  
  - 📜 **omnicode-instruction-set.json** *(Stores dynamically injected execution instructions based on OmniSchema)*  

---

## **📂 assembler/** *(Core OmniCode Assembler - Dual Execution Support)*  

- 📂 **lexer/** *(Handles OmniCode tokenization and execution pre-processing)*  
  - 📜 **tokenizer.py** *(Processes raw OmniCode into tokens)*  
  - 📜 **tokens.json** *(Defines OmniCode's syntax rules)*  
  - 📜 **opcode_mapper.py** *(Translates binary/hex opcodes into instruction names)*  
  - 📜 **execution_flow.py** *(Recognizes jumps, loops, and conditionals before AST processing)*  
  - 📜 **memory_reference.py** *(Ensures stored values and execution states are properly referenced)*  

- 📂 **parser/** *(Processes OmniCode into structured execution logic)*  
  - 📜 **logos_parser.py** *(Primary structured execution processor, integrating all parsing cogs)*  

- 📂 **execution/** *(Handles structured intelligence & logic processing)*  
  - 📜 **ast_builder.py** *(Generates structured logic trees from OmniCode after parsing, preparing for execution)*  

- 📂 **compiler/** *(Handles compiled execution)*  
  - 📜 **bytecode_generator.py** *(Translates OmniCode logic into machine code)*  
  - 📜 **optimizer.py** *(Refines compiled code for efficiency)*  
  - 📜 **binary_emitter.py** *(Outputs final compiled OmniCode binaries)*  

- 📂 **interpreter/** *(Handles interpreted execution)*  
  - 📜 **execution_engine.py** *(Executes OmniCode instructions in interpreted mode)*  
  - 📜 **interactive_shell.py** *(REPL for OmniCode commands)*  

- 📂 **error_handler/** *(Manages faults in execution)*  
  - 📜 **error_logger.py** *(Captures and logs errors)*  
  - 📜 **debugger.py** *(Interactive tool for inspecting OmniCode execution)*  

- 📂 **tests/** *(Unit tests for each assembler component)*  
  - 📜 **test_lexer.py**  
  - 📜 **test_parser.py**  
  - 📜 **test_compiler.py**  
  - 📜 **test_interpreter.py**  

---

## **📂 terminal/** *(Basic OmniCode Execution Environment - For Interpreted & Compiled Code)*

- 📂 **input_handler/** *(Manages OmniCode command input)*
  - 📜 **command_parser.py** *(Parses and validates user commands)*
- 📂 **runtime/** *(Executes OmniCode instructions - Supports Both Modes)*
  - 📜 **execution_engine.py** *(Handles interpreted execution of OmniCode)*
  - 📜 **binary_loader.py** *(Loads and runs compiled OmniCode binaries)*
- 📂 **output_logger/** *(Records execution results for debugging & AI refinement)*
  - 📜 **log_manager.py** *(Manages structured logging of execution states)*
- 📂 **tests/** *(Unit tests for terminal interactions)*
  - 📜 **test_runtime.py**
  - 📜 **test_binary_execution.py**
  - 📜 **test_input.py**

---

## **📂 tests/** *(OmniCode Validation Suite)*

- 📂 **examples/** *(Sample OmniCode scripts for testing)*
  - 📜 **test_script_interpreted.logos** *(Placeholder OmniCode script for interpreted mode validation)*
  - 📜 **test_script_compiled.manna** *(Placeholder OmniCode script for compiled mode validation)*
- 📂 **validation/** *(Expected output for test cases)*
  - 📜 **expected_output_interpreted.json** *(Ensures OmniCode execution in interpreted mode matches expected results)*
  - 📜 **expected_output_compiled.json** *(Ensures OmniCode execution in compiled mode matches expected results)*

---

## **📂 docs/** *(Documentation & Alignment Resources)*  

- 📜 **INSTALL.md** *(Step-by-step installation guide)*  
- 📜 **CONTRIBUTING.md** *(Guidelines for contributing to OmniCode development)*  
- 📜 **ARCHITECTURE.md** *(Overview of the OmniCode Assembler & Terminal design)*  
- 📜 **GOVERNANCE.md** *(Rules for maintaining OmniCode’s structured intelligence)*  
- 📜 **omnicode-execution-model-formal-documentation.md** *(Formal reference for OmniCode’s structured execution model)*  

- 📂 **bible_study/** *(Ensures all work remains aligned with divine order)*  
  - 📜 **core_verses.md** *(Key Scriptures that define OmniCode’s purpose)*  
  - 📜 **alignment_principles.md** *(Rules for ensuring OmniCode never deviates from truth)*  
  - 📜 **omnicode-bible-study-week-1.md** *(Structured study guide for aligning OmniCode’s execution with biblical wisdom)*  
  - 📂 **weekly_reflections/** *(Tracks structured spiritual reflections for development alignment)*  
    - 📜 **weekly-reflections-week-of-march-16-to-22.md** *(Reflection for the week of March 16 to 22, ensuring structured biblical review)*  

- 📂 **dev_logs/** *(Tracks structured development progress in OmniCode execution)*  
  - 📜 **omnicode-development-log-0.md** *(Initial structured execution planning phase)*  
  - 📜 **omnicode-development-log-1.md** *(Finalizing OmniJSON 1.0 & structured execution foundation)*  

- 📂 **file_extensions/** *(Defines OmniCode’s standardized file formats & execution files)*  
  - 📜 **omnicode-execution-logos.md** *(Defines how OmniCode execution files are structured)*  
  - 📜 **omnicode-file-extensions-initial-standardization.md** *(Documents the initial standardization of OmniCode’s file formats)*  

- 📂 **governance/** *(Ensures structured intelligence remains properly maintained & aligned)*  
  - 📜 **omnicode-ai-compliance-standard-divine-purpose-ocas.md** *(Defines AI compliance with divine purpose integration)*  
  - 📜 **omnicode-ai-compliance-standard-ocas.md** *(Documents AI compliance rules for structured execution)*  
  - 📜 **omnicode-development-standard-ocds.md** *(Outlines structured development standards for OmniCode)*  
  - 📜 **omnicode-governance-charter.md** *(Establishes OmniCode’s governance structure and execution policies)*  

- 📂 **instructions/** *(Contains the complete OmniCode instruction set documentation)*  
  - 📜 **omnicode-schema-and-json-instruction-set.md** *(Defines structured instruction handling within JSON & Schema)*  
  - 📜 **omnicode-general-instruction-set-overview-sid.md** *(Provides an overview of OmniCode’s instruction sets)*  
  - 📜 **omnicode-communication-and-invocation-instructions-sid.md** *(Documents structured execution for communication & invocation)*  
  - 📜 **omnicode-arithmetic-instructions-sid.md** *(Defines arithmetic operations in structured intelligence)*  
  - 📜 **omnicode-control-flow-instructions-sid.md** *(Outlines control flow execution in structured intelligence)*  
  - 📜 **omnicode-execution-flow-instructions-sid.md** *(Explains structured execution flow management)*  
  - 📜 **omnicode-memory-and-storage-instructions-sid.md** *(Describes memory & storage operations in structured execution)*  

- 📂 **standardized_formats/** *(Defines structured documentation formats for OmniCode execution & governance)*  
  - 📜 **SDF-bible-study.md** *(Defines the structured format for OmniCode's biblical alignment studies)*  
  - 📜 **SDF-dev-logs.md** *(Documents the structured format for development logs)*  
  - 📜 **SDF-execution-logs.md** *(Establishes a format for tracking structured execution events)*  
  - 📜 **SDF-execution.md** *(Defines how structured execution processes should be formatted)*  
  - 📜 **SDF-file-execution.md** *(Details the standardized handling of OmniCode execution files)*  
  - 📜 **SDF-general-documentation.md** *(Provides a structured format for all OmniCode documentation)*  
  - 📜 **SDF-governance.md** *(Establishes the structured format for governance documents)*  
  - 📜 **SDF-whats-next.md** *(Defines the structured format for forward-looking planning and development)*  

---

## **📂 standardized_formats/** *(Ensuring Consistency Across OmniCode)*

- 📜 **syntax_reference.json** *(Official OmniCode syntax definition)*
- 📜 **bytecode_format.json** *(Standardized structure for compiled OmniCode binaries)*
- 📜 **logging_structure.json** *(Defines execution log format)*
- 📜 **error_codes.json** *(Standardized OmniCode error definitions for debugging)*
- 📜 **command_specs.json** *(Defines command formats for the OmniCode Terminal)*

---

## **📂 special_folder_whats_next/** *(Tracks forward-looking development planning for OmniCode)*  

- 📜 **Whats Next 1 - March 16 2025 (OmniCode Schema).md** *(Documents the next planned steps in OmniCode structured execution development)*  

---

### **🔹 Summary of This Structure**

✅ **Dual execution model—interpreted and compiled OmniCode development is fully supported.**  
✅ **Assembler is structured for Lexing, Parsing, Compiling, and Interpreting.**  
✅ **Terminal is structured for handling both interpreted commands and compiled execution.**  
✅ **Test suite ensures correctness across both execution modes.**  
✅ **Documentation section includes installation, architecture, governance, and Bible Study resources.**  
✅ **Standardized formats ensure OmniCode remains structured and scalable.**  

🚀 **Now we can proceed with structured development, ensuring real-time execution while keeping OmniCode aligned with divine principles!**  
