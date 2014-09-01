zero-recursions
===============
def tozero(num)
if num <= 0
	puts num
else
	puts num
	tozero(num -1)
	end
end

puts tozero(10)
