# Duplicate-Cleanup
Clean up a folder containing files with duplicate files or unwanted characters in their names
- Change items: "-", "_", "()" to what ever you device
- Replace items in this line as well: $newName = $file.Name -replace "-|_|(\()|(\))|",""
