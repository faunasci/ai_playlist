## README.md

### Ai Generate Playlist

This script helps you create playlists of similar songs based on a given song. 

![me](https://github.com/faunasci/ai_playlist/blob/main/tty.gif)

**Purpose:**

- Creates a playlist with the recommended songs.
- Play the Playlist songs.
- Provides a playlist name .

**Requirements:**

- `ollama` in https://ollama.com/
	Install Linux
	curl -fsSL https://ollama.com/install.sh | sh
	
- `ytfzf` command-line tool in https://github.com/pystardust/ytfzf
	install Linux 
	sudo apt get install ytfzf

## Installation

Clone the repository:

```bash
git clone https://github.com/faunasci/ai_playlist.git
```

Make it executable:

```bash
chmod +x ai_playlist
```

Now you can run the script with:

**Usage:** 

```bash
./ai_playlist [options]
```

**Options:**

- -h (Show this Help)
- -n (number of music in the playlist), default 10
- -m (name model Ollama), default llama3
- -v (With Video), default No Video 
- -r (Choice Random Music,Artist) default No Random

**Example:**

```bash
ai_playlist -n 10 -m llama3 "Spain - Chick Corea"
```

**Features:**

- Handles historic playlists.
- Provides option to choose a previously created playlist.
- Uses Ollama AI model for song recommendations.

**Known Issues:**

- The Name of song may not always the good songs. Depend of Model.

**Contact:**

If you have any questions or suggestions, please feel free to contact the developer at [email protected]

