## Usage
Import `korwin` library by adding the following line to `Cargo.toml` of your project:

	korwin = "0.3"
Then call `generate` function to recive a quote as String

	let quote = korwin::generate();
	println!("Korwin quote of the day: {quote}");
