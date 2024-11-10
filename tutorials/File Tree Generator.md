# How to Generate a Directory Structure in Visual Studio Code using File Tree Generator

The **File Tree Generator** extension in Visual Studio Code is a handy tool that allows you to quickly create a text-based directory structure of your project. This can be useful for documenting the structure of your codebase in README files or other project documentation.

## Step 1: Install the File Tree Generator Extension

1. Open **Visual Studio Code**.
2. Navigate to the **Extensions** view by clicking on the Extensions icon in the sidebar or by pressing `Ctrl+Shift+X` on your keyboard.
3. In the search bar, type **"File Tree Generator"**.
4. Find the extension created by **Shinotatwu-DS** and click **Install**.
   - Alternatively, you can install it directly from the [Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=Shinotatwu-DS.file-tree-generator) by clicking the **Install** button, which will open Visual Studio Code and prompt you to confirm the installation.

## Step 2: Enable and Restart Visual Studio Code

After installation, it's best to **restart Visual Studio Code** to ensure the extension is fully enabled and functioning correctly.

## Step 3: Generate the File Tree

1. In Visual Studio Code, open the **Explorer** view by clicking the Explorer icon in the sidebar or pressing `Ctrl+Shift+E`.
2. Right-click on the root folder of your project (or any folder where you want to generate the tree structure).
3. From the context menu, select **Generate file tree to clipboard**.

## Step 4: Paste the File Tree

After selecting **Generate file tree to clipboard**, the file structure is copied to your clipboard. Now, you can paste it anywhere you need, such as:

- In a README.md file for documentation.
- In a separate `.txt` or `.md` file as part of your project documentation.
- In any document where you need a visual representation of your project structure.

To paste the copied file tree, simply go to the destination file and press `Ctrl+V` (or `Cmd+V` on macOS).

## Example Output

Here’s an example of what the file tree might look like:

```
ProjectRoot/
├── index.html
├── assets/
│   ├── images/
│   └── videos/
├── styles/
│   ├── main.css
│   └── main.scss
└── scripts/
    ├── app.js
    └── helper.js
```

And that’s it! You’ve successfully generated and pasted the file structure of your project using the **File Tree Generator** extension in Visual Studio Code.

---

## Additional Tips

- **Custom Depth**: You can configure the depth of the generated file tree in the extension settings.
- **Output as Markdown**: The extension supports different output formats, including Markdown, which can be useful for README files.
