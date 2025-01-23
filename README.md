# ERA_V3_Assignment_12

The aim of this assignment is to train a vanilla decoder only transfomer model with 124M ore parameters in such a way
that the test loss is less than  0.099999. 

# Model Parameters
Block Size: 1024 (max sequence length)
Vocabulary Size: 50,257 tokens
Number of Layers: 12
Number of Attention Heads: 12
Embedding Dimension: 768

# Training Hyperparameters:
Batch Size: 16
Sequence Length: 64
Number of Epochs: 15
Steps per Epoch: 1,000
Learning Rate: 1e-5
Optimizer: AdamW

# Average loss at the end of 15th epoch was 0.0778

# Generated sequences

Sequence 1:
Input: Gentlemen, for shame, forbear this outrage!
Tybalt, Mercutio, the prince expressly hath
Forbidden bandying in Verona streets:
Hold, Tybalt! good Mercutio!

MERCUTIO:
I am hurt.
A plague o'
Generated: Gentlemen, for shame, forbear this outrage!
Tybalt, Mercutio, the prince expressly hath
Forbidden bandying
**************************************************
Sequence 2:
Input:  both your houses! I am sped.
Is he gone, and hath nothing?

BENVOLIO:
What, art thou hurt?

MERCUTIO:
Ay, ay, a scratch, a scratch; marry, 'tis enough.
Where is my page? Go, villain
Generated:  both your houses! I am sped.
Is he gone, and hath nothing?

BENVOLIO:
What, art thou hurt
**************************************************

# Training logs

loaded 338025 tokens
1 epoch = 330 batches
Epoch 1/15: 100%|██████████| 1000/1000 [01:05<00:00, 15.28it/s, loss=5.8902]

Epoch 1/15:
Average Loss: 6.8099
Time: 65.43s
--------------------------------------------------
Epoch 2/15: 100%|██████████| 1000/1000 [01:04<00:00, 15.57it/s, loss=5.0023]

Epoch 2/15:
Average Loss: 5.5123
Time: 64.24s
--------------------------------------------------
Epoch 3/15: 100%|██████████| 1000/1000 [01:04<00:00, 15.57it/s, loss=4.1607]

Epoch 3/15:
Average Loss: 4.7546
Time: 64.24s
--------------------------------------------------
Epoch 4/15: 100%|██████████| 1000/1000 [01:04<00:00, 15.58it/s, loss=3.7901]

Epoch 4/15:
Average Loss: 4.0019
Time: 64.20s
--------------------------------------------------
Epoch 5/15: 100%|██████████| 1000/1000 [01:04<00:00, 15.57it/s, loss=2.4126]

Epoch 5/15:
Average Loss: 3.2329
Time: 64.22s
--------------------------------------------------
Epoch 6/15: 100%|██████████| 1000/1000 [01:04<00:00, 15.55it/s, loss=1.9612]

Epoch 6/15:
Average Loss: 2.4986
Time: 64.32s
--------------------------------------------------
Epoch 7/15: 100%|██████████| 1000/1000 [01:04<00:00, 15.52it/s, loss=1.5177]

Epoch 7/15:
Average Loss: 1.8630
Time: 64.42s
--------------------------------------------------
Epoch 8/15: 100%|██████████| 1000/1000 [01:04<00:00, 15.53it/s, loss=0.9336]

Epoch 8/15:
Average Loss: 1.3061
Time: 64.40s
--------------------------------------------------
Epoch 9/15: 100%|██████████| 1000/1000 [01:04<00:00, 15.50it/s, loss=0.6630]

Epoch 9/15:
Average Loss: 0.8446
Time: 64.50s
--------------------------------------------------
Epoch 10/15: 100%|██████████| 1000/1000 [01:04<00:00, 15.51it/s, loss=0.3157]

Epoch 10/15:
Average Loss: 0.5121
Time: 64.48s
--------------------------------------------------
Epoch 11/15: 100%|██████████| 1000/1000 [01:04<00:00, 15.57it/s, loss=0.2289]

Epoch 11/15:
Average Loss: 0.3039
Time: 64.22s
--------------------------------------------------
Epoch 12/15: 100%|██████████| 1000/1000 [01:04<00:00, 15.57it/s, loss=0.1277]

Epoch 12/15:
Average Loss: 0.1834
Time: 64.22s
--------------------------------------------------
Epoch 13/15: 100%|██████████| 1000/1000 [01:04<00:00, 15.59it/s, loss=0.1062]

Epoch 13/15:
Average Loss: 0.1320
Time: 64.15s
--------------------------------------------------
Epoch 14/15: 100%|██████████| 1000/1000 [01:04<00:00, 15.59it/s, loss=0.0802]

Epoch 14/15:
Average Loss: 0.0965
Time: 64.15s
--------------------------------------------------
Epoch 15/15: 100%|██████████| 1000/1000 [01:04<00:00, 15.59it/s, loss=0.0771]
Epoch 15/15:
Average Loss: 0.0778
Time: 64.13s
--------------------------------------------------
Training finished!
