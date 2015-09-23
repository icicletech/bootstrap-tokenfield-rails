require "bundler/gem_tasks"
require "fileutils"

desc 'Update the Bootstrap Tokenfield Javascript and CSS files'
task :update_bootstrap_tokenfield do
  def download_assets(version)
    base_url = 'https://raw.githubusercontent.com/sliptree/bootstrap-tokenfield'
    puts "Downlading Bootstrap Tokenfield - #{version}"
    `curl -o vendor/assets/javascripts/bootstrap-tokenfield.js \
      #{base_url}/v#{version}/dist/bootstrap-tokenfield.js `
    `curl -o vendor/assets/stylesheets/bootstrap-tokenfield.css \
      #{base_url}/v#{version}/dist/css/bootstrap-tokenfield.css`
    `curl -o vendor/assets/stylesheets/tokenfield-typeahead.css \
      #{base_url}/v#{version}/dist/css/tokenfield-typeahead.css`
  end

  FileUtils.mkdir_p('vendor/assets/javascripts')
  FileUtils.mkdir_p('vendor/assets/stylesheets')
  download_assets(BootstrapTokenfieldRails::VERSION)
  puts "Update Completed"
end
