# Music-genaration-using-Deeplearning
  Generating Irish Folk Tunes and Lyrics - using LSTM¶ This project uses Long Short-term Memory (LSTM) 
  based recurrent neural network (RNN) to generate music and lyrics using the  Nottingham Music Database
  
# Summary 
  We use the power of Deep Learning to train LSTM Networks to creatively generate Irish Folk Tunes
  
# Data Sets
  
 <h4>Irish Folk Music</h4>
 
   As a lover of folk tunes, particularly Irish tunes, I found these datasets immensely helpful.
   Nottingham Music dataset (ABC version of Nottingham music dataset: http://abc.sourceforge.net/NMD/)
  
 # Char RNN based Genarator
   The mechanics of the text generation uses a Char-RNN based generator, as decribed by Andrej Karpathy (http://karpathy.github.io/2015/05/21/rnn-effectiveness/)

  To create an RNN, specify the model_type as one 'lstm', 'rnn'. In general, the LSTM type networks have shown to be more effective
  
# ABC Music format
  The ABC Music format is a text-based music format.
   
    X:174
    T:Julia Delaney
    Z: id:dc-reel-161
    M:C
    L:1/8
    K:D Minor
     A|dcAG F2DF|E2CE F2DF|dcAG F2DF|Add^c defe|!
    dcAG F2DF|E2CE F2DF|dcAG F2DF|Add^c d3:|!
    e|fede fagf|ecgc acgc|fede fagf|edcA Adde|!
    fede fagf|ecgc acgc|fedf edcA|Add^c d3:|!
As can be seen, the format is incredibly compact. Each line begins with a single letter field (except for notes). ABC notation for music (link: http://abcnotation.com/)

# References 
  A few of the references that helped me. More useful for future work.
  
  Andrej Karpathy - Unreasonable Effectiveness of RNN https://karpathy.github.io/2015/05/21/rnn-effectiveness/
  
  Music Generation using RNN — with char-rnn https://maraoz.com/2016/02/02/abc-rnn/
