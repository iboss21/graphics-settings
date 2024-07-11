Visual Settings Configuration Guide
This guide provides detailed explanations and instructions for adjusting the visual settings in the visualsettings.dat file. Each section is commented to help you understand what each parameter does and how to modify it.

Height-Based Reflection Map
```lua
# Values to use with height based reflection map
heightReflect.width       100.00    # Width of the reflection map
heightReflect.height      220.00    # Height of the reflection map
heightReflect.specularoffset 1.00   # Specular offset for reflections
heightReflect.waterspeed  1.00      # Speed of water reflections
```

Rain Collision Map
```lua
# Values to use with rain collision map
raincollision.specularoffset 1.00   # Specular offset for rain collisions
raincollision.waterspeed     1.00   # Speed of rain collision reflections
```

Rain GPU Particle Effect
```lua
# Values for rain GPU particle effect
rain.NumberParticles        16384   # Number of particles for rain effect
rain.UseLitShader           1.0     # Use lit shader for rain particles (1.0 = true, 0.0 = false)

# Rain gravity settings
rain.gravity.x              1.0     # Gravity in the X direction
rain.gravity.y              0.0     # Gravity in the Y direction
rain.gravity.z             -0.98    # Gravity in the Z direction (falling down)

rain.fadeInScale            2.0     # Scale for fading in rain particles
rain.diffuse                1.0     # Diffuse light for rain particles
rain.ambient                0.4     # Ambient light for rain particles
rain.wrapScale              0.6     # Wrap scale for rain effect
rain.wrapBias               0.4     # Wrap bias for rain effect

# Rain default light color
rain.defaultlight.red       1.0     # Red component of light
rain.defaultlight.green     1.0     # Green component of light
rain.defaultlight.blue      1.0     # Blue component of light
rain.defaultlight.alpha    16.0     # Alpha (transparency) of light
```

General Weather Configuration
```lua
# General weather configuration
weather.CycleDuration                  240     # Duration of the weather cycle in seconds
weather.ChangeCloudOnSameCloudTypeChance 0.5   # Chance of changing clouds within the same type
weather.ChangeCloudOnSameWeatherTypeChance 0.5 # Chance of changing clouds within the same weather type
```

Sky Configuration
```lua
# Config for static values for skyhat
sky.sun.centreStart          0.98    # Start position of the sun
sky.sun.centreEnd            1.0     # End position of the sun
sky.cloudWarp                1.0     # Warp effect for clouds
sky.cloudInscatteringRange   0.68    # Inscattering range for clouds
sky.cloudEdgeSmooth          0.76    # Edge smoothing for clouds
sky.sunAxiasX                1.0     # Sun axis X value
sky.sunAxiasY                0.0     # Sun axis Y value
sky.GameCloudSpeed           0.0     # Speed of cloud movement
```

Cloud Shadows
```lua
# Config values for cloud shadows
shadows.cloudtexture.scale   1.0     # Scale of the cloud texture for shadows
shadows.cloudtexture.rangemin 0.0    # Minimum range for cloud shadows
shadows.cloudtexture.rangemax 1.0    # Maximum range for cloud shadows
```

Vehicle Settings
```lua
# Config values for vehicle settings

# Interior light color and intensity for cars
car.interiorlight.color.red          1.0    # Red component of interior light
car.interiorlight.color.green        1.0    # Green component of interior light
car.interiorlight.color.blue         0.7    # Blue component of interior light
car.interiorlight.intensity          1.5    # Intensity of interior light
car.interiorlight.radius             2.1    # Radius of the interior light
car.interiorlight.innerConeAngle     0.0    # Inner cone angle for light spread
car.interiorlight.outerConeAngle    90.0    # Outer cone angle for light spread
car.interiorlight.day.emissive.on    0.0    # Emissive property for daytime (on)
car.interiorlight.night.emissive.on  0.0    # Emissive property for nighttime (on)
car.interiorlight.day.emissive.off   0.0    # Emissive property for daytime (off)
car.interiorlight.night.emissive.off 0.0    # Emissive property for nighttime (off)
car.interiorlight.coronaHDR          1.0    # HDR effect for interior light
car.interiorlight.coronaSize         1.0    # Size of the corona effect for interior light
```

Adjusting Light and Other Parameters
To adjust the light settings, modify the values under the relevant sections. For example, to change the interior light color of cars:

1. Locate the sect
