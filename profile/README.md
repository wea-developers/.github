# wea

## What is wea?

Giving the package a meaning - wea stands for Wrapped Exchange Array. If you want to share array-packed data with different processes, remote nodes or different language executables ( yes, that's the vision ), wea is aiming to be a lean, lightweight and convenient alternative to [Protocol Buffers](https://developers.google.com/protocol-buffers) and Co.

It's inspired and adopted partly from Julia’s [InterProcessCommunication](https://github.com/emmt/InterProcessCommunication.jl) WrappedArray.

The wrapped exchange array can be accessed like a numpy array because under the hood, numpy is applied.

If this sounds good to you, just give it a try.
