# Legislative Document Style Guide

## Document Structure

1. **Metadata**: Begin the document with metadata information, including the title, jurisdiction, date, and other relevant details.

    * Required metadata

    ```markdown
    ---
    title: Title of the Legislation
    type: act
    jurisdiction: Jurisdiction Name
    date: YYYY-MM-DD
    number: 1
    ---
    ```

    * Optional metadata

    ```markdown
    ---
    repelled-by: ../path/to/file.md
    amended-by: ../path/to/file2.md
    ---
    ```

2. **Preamble**: Start with a preamble section, providing context, purpose, and any relevant background information.

    ```markdown
    # Preamble

    This legislation is enacted to [provide context or state the purpose].
    ```

3. **Sections and Articles**: Structure the document into sections, articles, and sub-subsections as necessary. Use numbered headings for clear hierarchy.

    ```markdown
    ## Section 1: Title

    ### Article 1.1: Subtitle

    #### § 1.1.1: Sub-subtitle

    #### § 1.1.2: Sub-subtitle 2

    ### Article 1.2: Subtitle 2
    ```

4. **Text Formatting**: Use Markdown for text formatting (e.g., bold, italics) to emphasize key points or definitions.

    - **Bold**: `**Bold text**`
    - *Italics*: `*Italic text*`

## Legislative Elements

1. **Definitions**: Define key terms in a dedicated section, typically at the beginning of the document.

    ```markdown
    ## Section 2: Definitions

    - **Term A**: [Definition of Term A]
    - **Term B**: [Definition of Term B]
    ```

2. **Enumerations and Lists**: Use numbered or bulleted lists for specifying items or points in the legislation.

    ```markdown
    - Item 1
    - Item 2
    1. Numbered Item 1
    2. Numbered Item 2
    ```

3. **Citations**: Cite relevant statutes, regulations, or other legal documents when necessary. Use a consistent citation style.

    ```markdown
    > The requirements of this legislation shall be in accordance with [Citation].
    ```

4. **References**: Provide references to related legislation or documents.

    ```markdown
    - See also [Related Legislation].
    ```

5. **Amendments**: Create a new document to mark any amendments to existing legislation. Use the contents of the existing legislation but add your amendments where necessary.

## Formatting Guidelines

1. **Language**: Use clear and concise English language. Avoid ambiguity and legalese when possible.

2. **Consistency**: Maintain a consistent style for headings, lists, and citations throughout the document.

3. **Spacing**: Use a single blank line between sections for readability.

## Additional Resources

- Consult your local legislative authority for jurisdiction-specific requirements.
- Seek legal expertise for complex legislative matters.
- Use Markdown rendering tools to produce professionally formatted documents.

Remember that legislative drafting is a complex and precise task. This style guide provides a basic framework for using Markdown, but it's important to follow the specific legislative requirements of your jurisdiction and consult legal experts to ensure compliance. You may see existing legislation for guidance.
