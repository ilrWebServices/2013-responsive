# More info at https://github.com/guard/guard#readme

guard 'sass',
  :input => 'www.ilr.cornell.edu',
  :output => './',
  :compass => true,
  :style => :compressed

guard 'livereload', :port => '35777' do
  watch(%r{.+\.(css|js)$})
end
