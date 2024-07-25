# 图片路径详解

## 绝对路径

绝对路径是指从网站根目录开始的完整路径。通常以 `/` 开头，用于指定网站的根目录下的文件或目录。

**示例**:

```html
<img src="/images/pic.jpg" alt="示例图片">
```

**英文版**:

```html
<img src="/images/pic.jpg" alt="Sample image">
```

在上面的示例中，`/images/pic.jpg` 表示从网站根目录开始，访问 `images` 文件夹中的 `pic.jpg` 文件。

## 相对路径

相对路径是相对于当前文件的位置来指定文件路径。可以根据文件的相对位置使用不同的符号来引用。

- **子关系**：`/` 用于引用当前目录下的子目录或文件。

  **示例**:

  ```html
  <img src="images/pic.jpg" alt="示例图片">
  ```

  **英文版**:

  ```html
  <img src="images/pic.jpg" alt="Sample image">
  ```

  在上面的示例中，`images/pic.jpg` 表示在当前目录下的 `images` 文件夹中的 `pic.jpg` 文件。

- **父关系**：`../` 用于引用当前目录的上一级目录。

  **示例**:

  ```html
  <img src="../images/pic.jpg" alt="示例图片">
  ```

  **英文版**:

  ```html
  <img src="../images/pic.jpg" alt="Sample image">
  ```

  在上面的示例中，`../images/pic.jpg` 表示从当前目录的上一级目录开始，访问 `images` 文件夹中的 `pic.jpg` 文件。

- **同级关系**：直接写文件名，或使用 `./` 表示当前目录。

  **示例**:

  ```html
  <img src="./pic.jpg" alt="示例图片">
  ```

  **英文版**:

  ```html
  <img src="./pic.jpg" alt="Sample image">
  ```

  在上面的示例中，`./pic.jpg` 表示在当前目录下的 `pic.jpg` 文件。

## 网络路径

网络路径是指通过 URL 访问的图片，通常以 `http://` 或 `https://` 开头。这种路径用于从互联网上的资源中加载图片。

**示例**:

```html
<img src="https://www.example.com/images/pic.jpg" alt="示例图片">
```

**英文版**:

```html
<img src="https://www.example.com/images/pic.jpg" alt="Sample image">
```

在上面的示例中，`https://www.example.com/images/pic.jpg` 是一个完整的网络路径，用于从指定的 URL 加载图片。