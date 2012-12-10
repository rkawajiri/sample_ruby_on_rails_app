require File.expand_path('../config/application', __FILE__)
require 'rake'

module ::SampleApp
  class Application
    include Rake::DSL
  end
end
module ::RakeFileUtils
  extend Rake::FileUtilsExt
end

SampleApp::Application.load_tasks
