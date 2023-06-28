
### Prerequisites

- Python >=3.8.0
- An OpenAI API key that can access OpenAI API (set up a paid account OpenAI account)
- Windows OS (Not tested on others)
- FFmpeg 


   
!!!. Create a `keys.py` file in the ecoute directory and add your OpenAI API key:

   - Option 1: You can utilize a command on your command prompt. Run the following command, ensuring to replace "API KEY" with your actual OpenAI API key:

      ```
      python -c "with open('keys.py', 'w', encoding='utf-8') as f: f.write('OPENAI_API_KEY=\"API KEY\"')"
      ```

   - Option 2: You can create the keys.py file manually. Open up your text editor of choice and enter the following content:
   
      ```
      OPENAI_API_KEY="API KEY"
      ```
      Replace "API KEY" with your actual OpenAI API key. Save this file as keys.py within the ecoute directory.

### Running

Run the main script:

```
python main.py --api
```

