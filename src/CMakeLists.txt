SET( EXE_NAME asteroids )

add_executable( ${EXE_NAME}
    Actor.cpp
    Asteroid.cpp
    CircleComponent.cpp
    Component.cpp
    Game.cpp
    InputComponent.cpp
    Laser.cpp
    Main.cpp
    Math.cpp
    MoveComponent.cpp
    Random.cpp
    Ship.cpp
    SpriteComponent.cpp
)

target_link_libraries( ${EXE_NAME}
    SDL2
    SDL2_image
)



