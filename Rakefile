desc "Starts up a development server that autostarts when a file changes"
task :dev do
  system "PORT=3000 rerun --ignore 'views/*,index.css' \"bundler exec rackup\""
end
