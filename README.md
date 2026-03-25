# Scratch-Animation
This is a simple scratch project done with Scratch a block based programming language.

#Bowl code ( Player movement)
when green flag clicked
forever
    if <key (right arrow) pressed?> then
        change x by 10
    end
    if <key (left arrow) pressed?> then
        change x by -10
    end
end
#apple code (falling+ falling)
when green flag clicked
set Score to 0
forever
    go to x: (pick random -200 to 200) y: 180
    repeat until <touching (Bowl) ?>
        change y by -5
    end
    change Score by 1
