function reverse_history_search
  history | fzf --no-sort | read -l command
  if test $command
    commandline -rb $command
  end
end
bind \cr reverse_history_search 

set PATH ~/.cargo/bin $PATH
set PATH ~/bin $PATH
