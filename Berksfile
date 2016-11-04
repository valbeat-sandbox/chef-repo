source "https://supermarket.chef.io"

cookbook 'mysql'
cookbook 'vim'
cookbook 'imagemagick'

def my_cookbook(name, options ={})
  cookbook(name, {
    git: "https://github.com/valbeat/#{name}.git" 
  }.merge(options))
end

# my_cookbook 'vim'
