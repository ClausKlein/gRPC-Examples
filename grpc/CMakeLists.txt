# Set examples list
set(examples greetings arithmetics)

foreach(example ${examples})
    add_subdirectory(${example})
endforeach()
