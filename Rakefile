desc "Package extension"
task :package do
  chrome_binary = '/Applications/Google\ Chrome.app/Contents/MacOS/Google\ Chrome'
  extension_dir = Dir.pwd
  extension_name = File.basename(extension_dir)
  pem_file = File.join(extension_dir, "#{extension_name}.pem")

  sh "#{chrome_binary} --pack-extension=#{extension_dir} --pack-extension-key=#{pem_file}"

  crx_file = File.join(extension_dir, "#{extension_name}.crx")
end
