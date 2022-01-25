# display_macro [![crates.io badge](https://img.shields.io/crates/v/display_macro)](https://crates.io/crates/display_macro)

```rust
use display_macro::{display, err_display};

fn main() {
	// print to stdout, always flushing
	display!("hello you");

	// print to stderr, always flushing
	err_display!("oh no, something happened!");
}
```
