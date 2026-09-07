source "https://rubygems.org"

# Deliberately unpinned, and no Gemfile.lock is committed (the repo's .gitignore excludes *.lock
# anyway). This app exists to exercise the Gemfile path of the deploy-to-itunesconnect-deliver
# Step's e2e tests: the Step runs `bundle install` to create the lockfile, then calls Fastlane
# through bundler. Resolving at run time keeps the fixture from going stale as Ruby moves on.
gem "fastlane"
