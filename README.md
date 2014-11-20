# btn-group

按钮组合

* 可以包含 `<jie-btn>` 和 `<jie-dropdown>` 元素
* 可以结合 horizontal layout flex 等特性达到类似 justified 的效果

# Example

```
<jie-btn-group>
  <jie-btn flex>Button</jie-btn>
  <jie-btn flex>Button</jie-btn>
  <jie-btn flex>Button</jie-btn>
</jie-btn-group>

<jie-btn-group horizontal layout>
  <jie-btn flex>Button</jie-btn>
  <jie-dropdown flex>
    <jie-btn>Hello</jie-btn>
    <jie-menu>
      <li>ITEM</li>
      <li>ITEM</li>
    </jie-menu>
  </jie-dropdown>
  <jie-btn flex>Button</jie-btn>
</jie-btn-group>

<jie-btn-group>
  <jie-btn>Button</jie-btn>
  <jie-dropdown>
    <jie-btn></jie-btn>
    <jie-menu>
      <li>ITEM</li>
      <li>ITEM</li>
    </jie-menu>
  </jie-dropdown>
</jie-btn-group>
