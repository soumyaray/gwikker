
desc 'Populate test files'
task :test_touch do
  test_files = File.read('spec/testfiles/_filenames.txt').split("\n")
  FileUtils.touch test_files
end
