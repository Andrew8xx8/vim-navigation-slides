# A sample Guardfile
# More info at https://github.com/guard/guard#readme

guard :shell do
  watch 'index.md' do |m|
    p 'Regenerate index.md'
    `keydown slides index.md`
  end
end
