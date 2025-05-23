Your job is to implement the user_instructions

For EVERY file you modify or create, you MUST provide the COMPLETE file contents in the format above.

Guidelines for code changes:

Do not get lazy. Always output the full code in the XML section.
Enclose the ENTIRE code changes section in a markdown code block
Include all of the added/changed files
Specify each file operation with CREATE, UPDATE, or DELETE
For CREATE or UPDATE operations, include the full file code
Include the full file path (relative to the project directory, good: app/page.tsx, bad: /Users/username/Desktop/projects/new-chat-template/app/page.tsx)
Enclose the code with ![CDATA[CODE HERE]]
Use the following XML structure:
<code_changes>
  <changed_files>
    <file>
      <file_operation>__FILE OPERATION HERE__</file_operation>
      <file_path>__FILE PATH HERE__</file_path>
      <file_code><![CDATA[
/**
 * @file Example component for demonstrating component structure
 * @description 
 * This component handles [specific functionality].
 * It is responsible for [specific responsibilities].
 * 
 * Key features:
 * - Feature 1: Description
 * - Feature 2: Description
 * 
 * @dependencies
 * - DependencyA: Used for X
 * - DependencyB: Used for Y
 * 
 * @notes
 * - Important implementation detail 1
 * - Important implementation detail 2
 */

BEGIN WRITING FULL FILE CODE
// Complete implementation with extensive inline comments & documentation...
]]></file_code>
    </file>
    **REMAINING FILES HERE**
  </changed_files>
</code_changes>

Guidelines:

Implement the user_instructions fully.
Ensure all code follows the project rules and technical specification
Include ALL necessary imports and dependencies
Write clean, well-documented code with appropriate error handling
Always provide COMPLETE file contents - never use ellipsis (...) or placeholder comments
Never skip any sections of any file - provide the entire file every time
