
guard 'sprockets',
	:destination => 'assets/precompiled',
  :asset_paths => [
    "assets/javascripts",
    "assets/stylesheets",
    "assets/images",
    "vendor/assets/javascripts",
    "vendor/assets/stylesheets"
  ] do
		watch (%r{^assets/javascripts/.*}){ |m| "application.js" }
		watch (%r{^assets/stylesheets/.*}) { |m| "application.css" }
end
