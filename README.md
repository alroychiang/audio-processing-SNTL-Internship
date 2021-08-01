`Batch Noise Remover.ipynb`
-  Removes Noise from all files in a directory. 
-  Change the .glob.glob(.....\*.wav) to directory of interest

`Convert Flac to Wav Code.ipynb`
- Just a simple code to rename audiofiles and their extensions

`Frame Check.ipynb`
- To check the Number of Frames, Duration & Framerate of a single audiofile

`Move to New Directory Code.ipynb`
- This is the hard-code to move specific microphones to their respective folders

`Nominalization Code.ipynb`
- Code to nominalize audio tracks

`Old Coversion and Nominalization 3.ipynb`
- Raw, old code used for the making of Nominalization Code.ipynb

`sevenChannel to 1,1 Channel to 7.ipynb`
- Splits a 7-Channel Audio File to 1-Channel Audio files, VIce versa

`Youtube Downloader Cleaned.ipynb`:
- To download and slice youtube videos from balanced_train_segments_propertext.xlsx, from http://research.google.com/audioset/download.html
- Each cell has a comment header `#___`, any cell that starts with `#test` are not part of the script's code. `#test` is only used when issues are faced wile running the code/ debugging
- `YTcommand_prompt.txt` Consist of command prompt lines of the downloaded YT-Vids
-`Snippets` consist of the sliced YT-Vids in accordance to the start & end timings of balanced_train_segments_propertext.xlsx


`Youtube Downloader OLD.ipynb`:

- Consist of all the test codes, debuggings and try and error codes that used to create Youtube Downloader Cleaned code.

- Any cell that begins with `#test`, `#testing`, `#one time use`, `#TO DOWNLOAD`, comments must be carefully read before running

 
`Single .Wav Noise Remover 2.0.ipynb`
- Consist of code to remove 'Noise Profile' from a single `.wav` file


`sevenChannel to 1,1 Channel to 7.ipynb`
- Consist of Code to split 7 channel audio files into mono-channel audio files, vice versa




```
  def add(x,y):
    # Adds two numbers
    return x+y
 ```
