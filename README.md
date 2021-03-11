# Quotes Generator

## Project description

Fine-tuned GPT2 model on the Quotes-500K dataset. For a given user prompt, it can generate motivational quotes starting with it. The model weights are deployed on Hugging Face Models Hub. 
Check it out at https://huggingface.co/nandinib1999/quote-generator.

## Training data

This is the distribution of the total dataset into training, validation and test dataset for the fine-tuning task.

<table style="width:30%">
<tr>
<th>train</th>
<td>349796</td>
</tr>
<tr>
<th>validation</th>
<td>99942</td>
</tr>
<tr>
<th>test</th>
<td>49971</td>
</tr>
</table>

## Training procedure

The model was fine-tuned using the Google Colab GPU for one epoch. The weights of the pre-trained GPT2 model were used as a base.

## Eval results

<table style="width:30%">
<tr>
<th>Epoch</th>
<th>Perplexity</th>
</tr>
<tr>
<td>1</td>
<td>15.180</td>
</tr>
</table>
