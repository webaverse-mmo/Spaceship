# Spaceship

This is a basic starting point for component read-me, below we show the code, and then use GPT to give and overall description of what is going on with the JSON / metaverse file.

### .metaversefile
```
{
  "name": "Spaceship",
  "start_url": "ToonSpaceship_v4.glb",
  "components": [
    {
      "key": "sit",
      "value": {
        "subtype": "saddle",
        "sitOffset": [0, -0.2, 0],
        "walkAnimation": ["wing_2_low|Take 001|BaseLayer", "wing_2_low001|Take 001|BaseLayer", "Object001|Take 001|BaseLayer", "Object002|Take 001|BaseLayer", "Object003|Take 001|BaseLayer", "Object004|Take 001|BaseLayer"],
        "walkAnimationHoldTime": 1,
        "walkAnimationSpeedFactor": 0.1,
        "speed": 0.02,
        "damping": 0.99
      }
    },
    {
      "key": "effect2",
      "value": {
        "effects": [
          {
            "type": "fire",
            "position": [-0.8, 0.5, 0.1],
            "quaternion": [-0.4999999999999999, -0.4999999999999999, -0.4999999999999999, 0.4999999999999999]
          },
          {
            "type": "fire",
            "position": [0.8, 0.5, 0.1],
            "quaternion": [-0.4999999999999999, -0.4999999999999999, -0.4999999999999999, 0.4999999999999999]
          }
        ]
      }
    }
  ]
}

```

`gpt3 interpretation`
This JSON code defines an object named "Spaceship" with a "start_url" property that refers to a 3D model file in glTF format ("ToonSpaceship_v4.glb"). The object also has two components defined: "sit" and "effect2".

The "sit" component specifies properties related to the way a user can sit on the spaceship, including the type of seat ("saddle"), the position offset for the user when seated, an array of animations to be played when the spaceship is moving ("walkAnimation"), the time to hold each animation frame ("walkAnimationHoldTime"), the speed factor to apply to the animations ("walkAnimationSpeedFactor"), the movement speed of the spaceship ("speed"), and a damping factor to apply to the spaceship's movement ("damping").

The "effect2" component defines an array of effects that can be added to the spaceship, including two "fire" effects at specific positions and orientations in the scene.
