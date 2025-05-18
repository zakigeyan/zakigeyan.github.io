# zakigeyan.github.io

## How to Run

Install Ruby and other prerequisites:

```bash
sudo apt-get install ruby-full build-essential zlib1g-dev
```

Add environment variables to `~/.bashrc` file:

```bash
echo '# Install Ruby Gems to ~/gems' >> ~/.bashrc
echo 'export GEM_HOME="$HOME/gems"' >> ~/.bashrc
echo 'export PATH="$HOME/gems/bin:$PATH"' >> ~/.bashrc
source ~/.bashrc
```

Check your Ruby, RubyGems, GCC, and Make version:

```bash
ruby -v
gem -v
gcc -v
g++ -v
make -v
```

Install Jekyll and Bundler:

```bash
gem install jekyll bundler
```

Install your Jekyll's dependencies:

```bash
bundle install
```

Run locally:

```bash
bundle exec jekyll serve
```

Your Jekyll site is running on http://127.0.0.1:4000.
