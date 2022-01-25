# display_macro

```rust
use display_macro::{display, err_display};

fn main() {
	// print to stdout, always flushing
	display!("hello you");
	// print to stderr, always flushing
	err_display!("oh no, something happened!");
}
```
