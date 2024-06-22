## Chronicled Wish Gacha System for Grasscutter
This project contains a Gacha system implementation for the Grasscutter emulator. The system includes proto definitions, Java classes, and configuration files necessary for the Gacha functionality.

## Directory Structure
root directory
├── data
│   └── Banners.json
├── proto
│   └── GachaInfo.proto
└── src
    └── main
        └── java
            └── emu
                └── grasscutter
                    └── game
                        └── gacha
                            ├── GachaBanner.java
                            ├── GachaSystem.java
                            └── PlayerGachaInfo.java
							

## Files and Purpose

### proto
- `GachaInfo.proto`: Protocol buffer definitions for Chronicled Wish Gacha information.

### data
- `Banners.json`: JSON configuration file for Chronicled Wish Gacha banners.

### src/main/java/emu/grasscutter/game/gacha
- `GachaBanner.java`: Class for handling Chronicled Wish Gacha banners.
- `GachaSystem.java`: Main class for the Chronicled Wish Gacha system logic.
- `PlayerGachaInfo.java`: Class for managing player-specific Chronicled Wish Gacha information.

## Building the Project
To compile the project and generate the JAR file, follow these steps:

1. Ensure you have Java Development Kit (JDK) installed.
2. Navigate to the project root directory.
3. Run the following command to compile the Java source files and build the JAR:

```sh
./gradlew jar
```

## Usage
After recompiling the JAR, you can integrate the Chronicled Wish Gacha system with your Grasscutter emulator by placing the generated JAR file in the appropriate directory.

## Contributing
If you wish to contribute to this project, please fork the repository and submit pull requests. Ensure that your code adheres to the project's coding standards and includes appropriate tests.

![Chronicled Wish Gacha](https://static0.gamerantimages.com/wordpress/wp-content/uploads/2024/03/genshin-impact-4-5-phase-1-new-chronicle-wish-banner-featured-characters.jpg)
