# StackRc

StackRc is a reference-counted pointer where the data may be owned by the stack.

This is useful if you want to have data which may be needed after the stack frame it is owned by is destroyed,
but you want to leave it on the stack as long as possible.