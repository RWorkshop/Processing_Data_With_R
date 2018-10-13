gettz: Get the Timezone Information
A function to retrieve the system timezone on Unix systems which has been found to find an answer when 'Sys.timezone()' has failed. It is based on an answer by Duane McCully posted on 'StackOverflow', and adapted to 
be callable from R. The package also builds on Windows, but just returns NULL.
