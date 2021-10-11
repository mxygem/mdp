# mdp (markdown preview)

CLI tool created while working through ["Powerful Command-Line Applications in Go](https://pragprog.com/titles/rggo/powerful-command-line-applications-in-go/) by Ricardo Gerardi.

## about

This tool will perform four main steps

1. Read the contents of the input Markdown file.
2. Use some Go external libraries to parse Markdown and generate a valid HTML block.
3. Wrap the results with an HTML header and footer.
4. Save the buffer to an HTML file which you can view in a browser.
