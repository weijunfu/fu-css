


# FU CSS

> 基于scss，参照tailwindcss实现样式原子化

## 颜色

<table>
    <tr>
        <th>&nbsp;</th>
        <th>50&nbsp;&nbsp;</th>
        <th>100</th>
        <th>200</th>
        <th>300</th>
        <th>400</th>
        <th>500</th>
        <th>600</th>
        <th>700</th>
        <th>800</th>
        <th>900</th>
        <th>950</th>
    </tr>
    <tr>
        <td>Red</td>
        <td style="background: oklch(0.971 0.013 7.38);"></td>
        <td style="background: oklch(0.936 0.032 17.717);"></td>
        <td style="background: oklch(0.885 0.062 18.334);"></td>
        <td style="background: oklch(0.808 0.114 19.571);"></td>
        <td style="background: oklch(0.704 0.191 22.216);"></td>
        <td style="background: oklch(0.637 0.237 25.331);"></td>
        <td style="background: oklch(0.577 0.245 27.325);"></td>
        <td style="background: oklch(0.505 0.213 27.518);"></td>
        <td style="background: oklch(0.444 0.177 26.899);color:#fff;"></td>
        <td style="background: oklch(0.396 0.141 25.723);color:#fff;"></td>
        <td style="background: oklch(0.258 0.092 26.042);color:#fff;"></td>
    <tr>
</table>

#### 示例

<table>
    <tr>
        <th>Class</th>
        <th>Style</th>
    </tr>
    <tr>
        <td>text-color-red-50</td>
        <td>
            <pre>
                <code>
.text-red-50 {
    color: var(--color-red-50);
}</code>
            </pre>
        </td>
    </tr>
    <tr>
        <td>border-red-50</td>
        <td>
            <pre>
                <code>
.border-red-50 {
    border-color: var(--color-red-50);
}</code>
            </pre>
        </td>
    </tr>
    <tr>
        <td>bg-red-50</td>
        <td>
            <pre>
                <code>
.bg-red-50 {
    background-color: var(--color-red-50);
}</code>
            </pre>
        </td>
    </tr>
    <tr>
        <td>outline-red-50</td>
        <td>
            <pre>
                <code>
.outline-red-50 {
    outline-color: var(--color-red-50);
}</code>
            </pre>
        </td>
    </tr>
    <tr>
        <td>decoration-red-50</td>
        <td>
            <pre>
                <code>
.decoration-red-50 {
    text-decoration-color: var(--color-red-50);
}</code>
            </pre>
        </td>
    </tr>
    <tr>
        <td>accent-red-50</td>
        <td>
            <pre>
                <code>
.accent-red-50 {
    accent-color: var(--color-red-50);
}</code>
            </pre>
        </td>
    </tr>
    <tr>
        <td>caret-red-50</td>
        <td>
            <pre>
                <code>
.caret-red-50 {
    caret-color: var(--color-red-50);
}</code>
            </pre>
        </td>
    </tr>
</table>