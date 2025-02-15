# Make Your Own VBScript Tutorial

Welcome to the **Make Your Own VBScript** tutorial! This guide will teach you the basics of VBScript, a simple scripting language used for automation tasks on Windows machines.

## Table of Contents
1. [What is VBScript?](#what-is-vbscript)
2. [Creating Your First VBScript](#creating-your-first-vbscript)
3. [Variables and Data Types](#variables-and-data-types)
4. [Control Flow Statements](#control-flow-statements)
5. [Functions in VBScript](#functions-in-vbscript)
6. [Error Handling](#error-handling)
7. [Conclusion](#conclusion)

---

## What is VBScript?

**VBScript** (Visual Basic Scripting Edition) is a lightweight scripting language developed by Microsoft. It is used primarily for automation and scripting tasks on Windows. It is similar to Visual Basic, but it is interpreted rather than compiled.

- It’s widely used in **Windows scripting**, **web development**, and **automation tasks**.
- Typically used for tasks like file manipulation, sending emails, and interacting with system services.

---

## Creating Your First VBScript

To create your first VBScript:

1. Open **Notepad** (or any text editor).
2. Type the following code:

    ```vbscript
    WScript.Echo "Hello, World!"
    ```

3. Save the file with a `.vbs` extension (for example, `HelloWorld.vbs`).
4. Double-click the file to execute it, and you should see a pop-up message saying "Hello, World!"

---

## Variables and Data Types

In VBScript, variables do not require a declaration before they are used. However, it’s good practice to use `Dim` to define variables.

### Example:

```vbscript
Dim message
message = "Hello, VBScript!"
WScript.Echo message
