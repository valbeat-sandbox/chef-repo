source "https://supermarket.chef.io"

cookbook 'mysql'
cookbook 'vim'
cookbook 'imagemagick'



# 自分のレポジトリから落とす
def my_cookbook(name, options ={})
  cookbook(name, {
    git: "https://github.com/valbeat/#{name}.git" 
  }.merge(options))
end

my_cookbook 'setup-mysql'
