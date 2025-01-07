# Example RosLibRust Package

The point of this package is provide a good example of how to integrate roslibrust into a package using the proc macro,
and shows good style on how to use roslibrust's generic traits.

Use `cargo run` to run the example and see it publish messages to a topic.

The example will fail if an instance of rosbridge is not running on port 9090.

Use `cargo test` to run the example's tests.

Note: the test runs in 0.00s on a reasonable machine due to the use of tokio's time mocking feature.
