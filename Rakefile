CC = "gcc"
 
task :default => "hello"
 
file "hello" => "hello.o" do
	  sh "#{CC} -o hello hello.o"
end
 
file "hello.o" => "hello.c" do
	  sh "#{CC} -c hello.c"
end
