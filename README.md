# SDU-SPRO3-LATEX

<center><h1>!!! Read before contributing !!!</h1></center>
Here are some quick tips to make contributing to the LaTeX repository easier for everyone:

<h4>PDF's:</h4>
Remember not to upload the generated .pdf files to the repository. Use the git staging and commit features to avoid unnecessary merge requests.

<h4>Images:</h4>
When adding an image, use a relative path instead of an absolute path. The image folder is the root for all PNG or JPG images, so just use 'image_name.png' as the path, without adding the folder name.

<h4>Remote push and pull (sync):</h4>
If you encounter an error while pushing local changes to the remote, it's likely because someone else has already pushed their changes. The quick fix is to rebase your local repository to include the remote changes.

<h4>Commit message:</h4>
When writing commit messages, keep them short and meaningful. For example, 'Update: Spelling in ADC section.' This makes it easier to manage merge or revert requests.

<h4>Merge conflicts will happen</h4>
By following the steps above, the chances of encountering merge conflicts should be minimized. If you're unsure about what you're doing, reach out to a more experienced team member for assistance.

<h4>Clear your pending changes before pulling, pushing or syncing</h4>
A common mistake is having pending local changes when trying to pull new changes from the remote. Easily resolve this by either committing and pushing your current changes or discarding them. Failure to do so may result in an error – refer to the 'Remote push and pull (sync)' section for guidance.