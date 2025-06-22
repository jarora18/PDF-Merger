# PDF-Merger

## Usage

1. **Clone the Repository**

2. **Set the paths**

   Modify the script to include the paths of the PDFs you want to merge and the output file name. Example:

   ```python
   input_pdfs = ["/path/to/part1.pdf", "/path/to/part2.pdf"]
   output_pdf = "merged_output.pdf"
   merge_pdfs(input_pdfs, output_pdf)
   ```

3. **Run the Script**

   ```bash
   python merge_pdfs.py
   ```

4. **Merged PDF**

   The merged PDF will be saved with the name specified in the `output_pdf` variable.

### merge_pdfs Function

This function takes two arguments:
- `input_pdfs`: A list of paths to the input PDF files to be merged.
- `output_pdf`: The path where the merged PDF file will be saved.
