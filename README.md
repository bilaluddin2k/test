# test

mkdir -p ~/.eternal/
PROMPT_COMMAND=${PROMPT_COMMAND:+$PROMPTCOMMAND ; }" 'echo $$ $USER $(who -m | cut -c10-15) $(who -m | cut -c40- ) \ "$(history 1| cut -c8-)"
>> ~/.eternal/.bash_eternal_history_$(id -un)_ `date +%d_%m_%Y`'



source /etc/bashrc
