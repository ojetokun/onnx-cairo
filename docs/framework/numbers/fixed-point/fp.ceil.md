# fp.ceil

```rust
fn ceil(self: FixedType) -> FixedType;
```

Returns the smallest integer greater than or equal to the fixed point number.

## Args

*`self`(`FixedType`) - The input fixed point

## Returns

The smallest integer greater than or equal to the input fixed point number.

## Examples

```rust
fn ceil_fp_example() -> FixedType {
    // We instantiate fixed point here.
    let fp = FixedTrait::from_felt(194615506); // 2.9
    
    // We can call `ceil` function as follows.
    fp.ceil()
}
>>> {mag: 201326592, sign: false} // = 3
```
