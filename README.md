# [React](https://reactjs.org/) &middot; [![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/facebook/react/blob/master/LICENSE) [![npm version](https://img.shields.io/npm/v/react.svg?style=flat)](https://www.npmjs.com/package/react) [![CircleCI Status](https://circleci.com/gh/facebook/react.svg?style=shield&circle-token=:circle-token)](https://circleci.com/gh/facebook/react) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://reactjs.org/docs/how-to-contribute.html#your-first-pull-request)

React是一个用于构建用户界面的JavaScript库。

* **Declarative:** React使创建交互式UI变得轻松。为应用程序中的每个状态设计简单的视图，并且react将在数据更改时有效地更新和呈现正确的组件。声明性视图使代码更易于预测、理解和调试。
* **Component-Based:** 构建管理自己状态的封装组件，然后组合它们以生成复杂的UI。由于组件逻辑是用JavaScript而不是模板编写的，所以您可以轻松地通过应用程序传递丰富的数据，并将状态保存在DOM之外。
* **Learn Once, Write Anywhere:** 我们不假设您的技术堆栈的其余部分，因此您可以在React中开发新功能，而无需重写现有代码。React还可以使用节点在服务器上呈现，并使用 [React Native](https://facebook.github.io/react-native/).

[了解如何在自己的项目中使用react]（https://reactjs.org/docs/getting started.html）。

## Installation

React从一开始就是为逐渐采用而设计的，并且 **你可以用你所需要的很少或最多的反应**:

* Use [Online Playgrounds](https://reactjs.org/docs/getting-started.html#online-playgrounds) to get a taste of React.
* [Add React to a Website](https://reactjs.org/docs/add-react-to-a-website.html) as a `<script>` tag in one minute.
* [Create a New React App](https://reactjs.org/docs/create-a-new-react-app.html) if you're looking for a powerful JavaScript toolchain.

You can use React as a `<script>` tag from a [CDN](https://reactjs.org/docs/cdn-links.html), or as a `react` package on [npm](https://www.npmjs.com/).

## Documentation

You can find the React documentation [on the website](https://reactjs.org/docs).  

Check out the [Getting Started](https://reactjs.org/docs/getting-started.html) page for a quick overview.

The documentation is divided into several sections:

* [Tutorial](https://reactjs.org/tutorial/tutorial.html)
* [Main Concepts](https://reactjs.org/docs/hello-world.html)
* [Advanced Guides](https://reactjs.org/docs/jsx-in-depth.html)
* [API Reference](https://reactjs.org/docs/react-api.html)
* [Where to Get Support](https://reactjs.org/community/support.html)
* [Contributing Guide](https://reactjs.org/docs/how-to-contribute.html)

You can improve it by sending pull requests to [this repository](https://github.com/reactjs/reactjs.org).

## Examples

We have several examples [on the website](https://reactjs.org/). Here is the first one to get you started:

```jsx
function HelloMessage({ name }) {
  return <div>Hello {name}</div>;
}

ReactDOM.render(
  <HelloMessage name="Taylor" />,
  document.getElementById('container')
);
```

此示例将把“hello taylor”呈现到页面上的容器中。

您会注意到我们使用了类似HTML的语法；[我们称之为JSX]（https://reactjs.org/docs/introducing jsx.html）。JSX不需要使用react，但它使代码更具可读性，并且编写起来就像编写HTML。如果您将react用作`<script>`标记，请在集成JSX时阅读[本节]（https://reactjs.org/docs/add-react-to-a-website.html可选，尝试与JSX反应）；否则[建议的javascript工具链]（https://reactjs.org/docs/create-a-new-react-app.html）会自动处理它。

## Contributing

此存储库的主要目的是继续发展react core，使其更快、更容易使用。React的开发是在Github上公开进行的，我们感谢社区为错误修复和改进做出的贡献。阅读下面的内容，了解如何参与改进反应。

### [Code of Conduct](https://code.fb.com/codeofconduct)

Facebook已经采纳了我们希望项目参与者遵守的行为准则。请阅读[全文]（https://code.fb.com/codeofconduct），以便您了解哪些行为是可以容忍的，哪些行为是不可以容忍的。

### [Contributing Guide](https://reactjs.org/contributing/how-to-contribute.html)

阅读我们的[贡献指南]（https://reactjs.org/contributing/how-to-contribute.html），了解我们的开发过程、如何建议错误修复和改进，以及如何构建和测试您的更改以做出反应。

### Good First Issues

为了帮助您充分了解我们的贡献过程，我们列出了[良好的第一问题]（https://github.com/facebook/react/labels/good%20first%20issue），其中包含范围相对有限的错误。这是一个很好的开始的地方。

### License

React is [MIT licensed](./LICENSE).
