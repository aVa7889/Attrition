

### attrition
Neural Network Dense model
Picked X parameters
shared layer: relu
Attrition output: sigmoid
Department output: sigmoid
Attrition predictions accuracy: 0.796
Department predictions accuracy: 0.560

### attrition2
Neural Network Dense model
X parameters per correlation() 
shared layer: relu
input_layer = shape=(input_nodes,)
Attrition output: sigmoid
Department output: softmax
shared1 = layers.Dense(64, activation='relu')(input_layer)
shared2 = layers.Dense(128, activation='relu')(shared1)
Attrition predictions accuracy: 0.818
Department predictions accuracy: 0.587

### attrition3
Neural Network Dense model
X parameters per correlation()
train_test_split, random_state=1
input_layer = X_df.shape[1]
shared_layer1 = layers.Dense(64, activation='relu')(input_layer)
shared_layer2 = layers.Dense(32, activation='relu')(shared_layer1)
shared layer: relu
Attrition output: sigmoid
Department output: softmax
Attrition Accuracy: 0.83423912525177
Department Accuracy: 0.676630437374115