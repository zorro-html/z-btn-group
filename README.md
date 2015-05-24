# `<z-btn-group>`

A group element which contains buttons or dropdowns

- could contains `<z-btn>` or `<z-dropdown>` elements
- could add attributes like `[horizontal]` `[layout]` `[flex]` to make `justified` effect
- could add attributes `[radio]` or `[multi]` to enable radio / checkbox style selection

## Import

```
<link rel="import" href="z-btn-group/z-btn-group.html">
```

## Attributes

- `radio`: enable single selection mode
- `multi`: enable multi selection mode

## Examples

```
<z-btn-group>
  <z-btn>Button</z-btn>
  <z-btn>Button</z-btn>
  <z-btn>Button</z-btn>
</z-btn-group>

<z-btn-group>
  <z-dropdown>
    <z-btn>Button</z-btn>
    <z-menu>
      <li>ITEM</li>
      <li>ITEM</li>
    </z-menu>
  </z-dropdown>
  <z-btn>Button</z-btn>
  <z-btn>Button</z-btn>
</z-btn-group>

<z-btn-group>
  <z-btn>Button</z-btn>
  <z-dropdown>
    <z-btn>Button</z-btn>
    <z-menu>
      <li>ITEM</li>
      <li>ITEM</li>
    </z-menu>
  </z-dropdown>
  <z-btn>Button</z-btn>
</z-btn-group>
```

### Button Group Block

```
<z-btn-group horizontal layout>
  <z-btn flex>Button</z-btn>
  <z-btn flex>Button</z-btn>
  <z-btn flex>Button</z-btn>
</z-btn-group>
```

### Radio Button Group

```
<z-btn-group radio>
  <z-btn>Radio Button</z-btn>
  <z-btn>Radio Button</z-btn>
  <z-btn active>Radio Button</z-btn>
</z-btn-group>
```

### Checkbox Button Group

```
<z-btn-group multi>
  <z-btn active>Checkbox Button</z-btn>
  <z-btn>Checkbox Button</z-btn>
  <z-btn active>Checkbox Button</z-btn>
</z-btn-group>
```

### Split Button

```
<z-btn-group>
  <z-btn>Button</z-btn>
  <z-dropdown>
    <z-btn></z-btn>
    <z-menu>
      <li>ITEM</li>
      <li>ITEM</li>
    </z-menu>
  </z-dropdown>
</z-btn-group>
```
