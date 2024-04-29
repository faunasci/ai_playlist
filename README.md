## README.md

### Ai Playlist

This script helps you create playlists of similar songs based on a given song. 

https://github.com/faunasci/ai_playlist/assets/168428584/b6815364-8169-43aa-88f9-10023f4c12a3

**Purpose:**

- Creates a playlist with the recommended songs.
- Play the Playlist songs.
- Provides a playlist name .

**Requirements:**

- `ollama` in https://ollama.com/

  	*Linux Install*

	```bash
	curl -fsSL https://ollama.com/install.sh | sh
	```
 
- `ytfzf` command-line tool in https://github.com/pystardust/ytfzf

	*Linux Install*

	```bash
 	sudo apt get install ytfzf
	```

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

start the server:

```bash
./ollama serve
```
Finally, in a separate shell

```bash
./ai_playlist [options]
```
Type 'q' for change music and 2x 'q' for Quit loop.

**Options:**

- -h  (Show this Help)
- -n  (number of music in the playlist), default 10
- -m  (name model Ollama), default llama3
- -v  (With Video), default No Video 
- -r  (Choice Random Music,Artist) default No Random

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

