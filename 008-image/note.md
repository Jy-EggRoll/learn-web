# 图片

## 网页中被大量使用的元素

`<img>`

```html
<img src="example.jpg" alt="描述文本" title="悬停提示文本" width="300" height="200">
```

**英文版**:

```html
<img src="example.jpg" alt="Description text" title="Hover text" width="300" height="200">
```

### 详解：

1. **src**：路径（`src` 是 `source` 的缩写），指定图片的文件路径或 URL。它是 `<img>` 标签中必需的属性。

   **英文版**: `src` stands for `source` and specifies the path or URL of the image file. It is a required attribute of the `<img>` tag.

2. **alt**：图片的替代文本（当图片无法显示时会显示这段文本），对于屏幕阅读器用户和搜索引擎优化（SEO）也很重要。

   **英文版**: `alt` stands for alternative text, which is displayed when the image cannot be shown. It is also important for screen readers and search engine optimization (SEO).

3. **title**：鼠标的悬停文本，当用户将鼠标悬停在图片上时显示的提示文本。

   **英文版**: `title` is the hover text that appears when the user hovers their mouse over the image.

4. **width** 和 **height**：规定图片的宽度和高度，可以使用像素值（如 `300px`）或百分比（如 `50%`）。这些属性用于控制图片的显示尺寸。

   **英文版**: `width` and `height` specify the dimensions of the image. You can use pixel values (e.g., `300px`) or percentages (e.g., `50%`). These attributes control the display size of the image.

### 注意事项

- **单标签**：`<img>` 是一个自封闭的单标签，不需要结束标签。

  **英文版**: `<img>` is a self-closing tag and does not require a closing tag.

- **响应式设计**：为了让图片在不同设备上自适应，可以使用 CSS 来控制图片的尺寸，例如使用 `max-width: 100%;`。

  **英文版**: For responsive design, you can use CSS to control the image size, for example, using `max-width: 100%;` to make the image fit its container.