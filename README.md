# ChatBot-Llama2-Finetuned
In this project I finetuned [Llama-2](https://huggingface.co/meta-llama/Llama-2-7b-chat-hf) on a chat conversation dataset for creating a chatbot trained on conversations with friends.
I used LoRA for better finetuning using Google Colab.
My dataset had about 200k chat messages, used %80 for training and %20 for evaluation.
I am inpired by that [video](https://youtu.be/OVqe6GTrDFM?si=SyhBwFA8pkzExK1_)

## Training Progress
<table>
  <tr>
    <th>Step</th>
    <th>Training Loss</th>
  </tr>
  <tr>
    <td>10</td>
    <td>3.450300</td>
  </tr>
  <tr>
    <td>20</td>
    <td>2.532200</td>
  </tr>
  <tr>
    <td>30</td>
    <td>2.152300</td>
  </tr>
  <tr>
    <td>40</td>
    <td>1.998500</td>
  </tr>
  <tr>
    <td>50</td>
    <td>1.989000</td>
  </tr>
  <tr>
    <td>60</td>
    <td>1.868900</td>
  </tr>
  <tr>
    <td>70</td>
    <td>1.834800</td>
  </tr>
  <tr>
    <td>80</td>
    <td>1.776800</td>
  </tr>
  <tr>
    <td>90</td>
    <td>1.761100</td>
  </tr>
  <tr>
    <td>100</td>
    <td>1.760700</td>
  </tr>
  <tr>
    <td>110</td>
    <td>1.795400</td>
  </tr>
  <tr>
    <td>120</td>
    <td>1.738700</td>
  </tr>
</table>
