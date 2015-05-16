# dependecies

require 'rake'
require 'yaml'
require 'fileutils'
require 'rbconfig'

# configuration
task :default => :watch
# load configuration file
CONFIG = YAML.load_file("_config.yaml")

# get and parse date
DATE = Time.now.strftime("%Y-%m-%d")
TIME = Time.now.strftime("%H:%M:%S")
POST_TIME = DATE + ' ' + TIME

# directories
POSTS = "_posts"
DRAFTS = "_drafts"