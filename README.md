## Step 0:

Please refer to the [SETUP.md](./SETUP.md) file.

## Step 1 - Creation of the Enemy:

### 📑 **Description**:

In this step, we will create an enemy object using a [3D Cube](https://docs.unity3d.com/Manual/class-Cube.html) and set it up for movement.

### 📌 **Tasks**:

- Create an empty [GameObject](https://docs.unity3d.com/Manual/class-GameObject.html) and drag a cube into it.
- Place two waypoints 10 units away from the cube along the x and y axis, respectively, using the [Transform component](https://docs.unity3d.com/ScriptReference/Transform.html).

## Step 2 - Creation of the Enemy Movement Script:

### 📑 **Description**:

In this step, we will create a [script](https://docs.unity3d.com/Manual/Quickstart3DCreate.html#Scripting) that will control the movement of the enemy.

### 📌 **Tasks**:

- Create a script called EnemyMovement.
- Retrieve the two waypoints in the script using the [Transform component](https://docs.unity3d.com/ScriptReference/Transform.html).
- Move the enemy from waypoint 1 to waypoint 2 using the script, by updating the [Transform component](https://docs.unity3d.com/ScriptReference/Transform.html) of the enemy GameObject.

## Step 3 - Generating Enemies:

### 📑 **Description**:

In this step, we will use the map creation script to randomly generate enemies.

### 📌 **Tasks**:

- Revisit the map creation script.
- Create an enemy every time a new floor is created.
- Make this creation random, with a 10% chance, using the [Random.Range](https://docs.unity3d.com/ScriptReference/Random.Range.html) function.
- Use the [OnCollisionEnter](https://docs.unity3d.com/ScriptReference/MonoBehaviour.OnCollisionEnter.html) function to handle collisions with enemies and kill the player.

## Step 4 (Bonus) - Movement Angle:

### 📑 **Description**:

In this bonus step, we will modify the movement of the enemy to follow a different angle.

### 📌 **Tasks**:

- To move the enemy along a different angle, modify the enemy's `transform.position` based on the desired angle and a set speed, using the [Transform component](https://docs.unity3d.com/ScriptReference/Transform.html) and trigonometry functions such as [Mathf.Sin](https://docs.unity3d.com/ScriptReference/Mathf.Sin.html) and [Mathf.Cos](https://docs.unity3d.com/ScriptReference/Mathf.Cos.html).

## Step 5 (Bonus) - Voxel:

### 📑 **Description**:

In this bonus step, we will create sprites using an object via [Voxel](https://en.wikipedia.org/wiki/Voxel).

### 📌 **Tasks**:

- Create sprites using an object via Voxel (Bonus Bonus Bonus).
