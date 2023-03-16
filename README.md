 # REMA ➕
 
 <img src="https://img.shields.io/badge/%F0%9F%8E%89%20CS%20210%20Best%20Of-Category%3A%20Clear%20Value%20Proposition-brightgreen"/>
 
### AI Assistant to Automate Medical Coding

https://user-images.githubusercontent.com/66540748/225138370-22ac9320-ac45-478f-bcb0-367cab45ac22.mov
 
Read more through our [wiki](https://github.com/cs210/2023-Unusual-Ventures-1/wiki/REMA-Home)

## How it works

Our site takes in clinical notes as input, then prompts Open AI's text davinci 003 model to identify the correct ICD-10 codes as well as cite its justifications. We verify all ICD-10 codes and their descriptions by cross-referencing output with the [CMS.gov database](https://www.cms.gov/Medicare/Coding/ICD10/2018-ICD-10-CM-and-GEMs). We use Stanford CRFM Helm's API to access the model. 

## Running Locally

After cloning the repo, go to [Stanford CRFM Helm](https://crfm.stanford.edu/helm/v0.1.0/) to receive an API key. 

Then, run the application in the command line and it will be available at `http://localhost:3000`.

```bash
vercel dev 
```

## Credits

We would like to credit our landing page design and parts of frontend source code to this [starter project](https://github.com/Nutlope/twitterbio).
