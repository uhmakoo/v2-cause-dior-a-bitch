# Discord Auto Messenger

This Python script enables automated messaging in a Discord channel, enhancing the experience by sending messages from a chat dataset to mimic human-like behavior.

## Installation

### Local Machine

1. Clone the repository or download the code as a zip file and extract it to a folder.
2. Navigate to the project directory in your terminal:

    ```
    cd /Downloads/@uhmako/
    ```

3. (Optional) Customize the message content by editing **messages.txt**, adding messages on separate lines. By default, random messages are provided.

## Usage

Execute the script using the following command:

```
python auto.py
```

During execution, you'll be prompted to specify the duration in seconds between each message and the sleep interval after each cycle.

## Options

The script offers the following options:

`--config`: Configure user information by providing user ID, Discord token, Discord channel URL, and Discord channel ID:

```
python auto.py --config
```

`--setC`: Set the channel for message delivery by providing the Discord channel URL and channel ID:

```
python auto.py --setC
```

`--help`: Display help information for the script and its available options:

```
python auto.py --help
```

## Contributing

Please dont forget to show some support since i am giving this for free and dont skid it my discord tag should be the file name @uhmako
