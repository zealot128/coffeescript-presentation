desc "build"
task :build do

  puts `cd presentation/ && middleman build`
  puts `rsync -a presentation/build/ .`

end
