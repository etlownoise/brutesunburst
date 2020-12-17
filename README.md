# brutesunburst
Raw C# code to bruteforce sunburst hashes 
ET Lownoise 2020

	This by no means is the most efficient way to crack the sunburst hashes, i just wanted to learn a little more about the backdoor by bruteforcing
  the Sunburst hashes. However Fireeye already had cracked most of them (https://github.com/fireeye/sunburst_countermeasures/blob/main/fnv1a_xor_hashes.txt) 
	Still there are 22 hashes not cracked. I have left those defined in notdecoded_hashesb[] for someone with better hardware to try to brake them.

Hashes still not cracked:

      			10501212300031893463UL,
			12785322942775634499UL,
			13655261125244647696UL,
			13783346438774742614UL,
			13852439084267373191UL,
			14243671177281069512UL,
			14695981039346656037UL,
			1475579823244607677UL,
			15514036435533858158UL,
			155978580751494388UL,
			16066651430762394116UL,
			16112751343173365533UL,
			17624147599670377042UL,
			17956969551821596225UL,
			18446744073709551613UL,
			2380224015317016190UL,
			2589926981877829912UL,
			3320767229281015341UL,
			3425260965299690882UL,
			6605813339339102567UL,
			7574774749059321801UL,
			9234894663364701749UL

References:

  Combinations Code from Eric Lippert https://stackoverflow.com/questions/3093622/generating-all-possible-combinations/3098381#3098381		
	FNV http://en.wikipedia.org/wiki/Fowler%E2%80%93Noll%E2%80%93Vo_hash_function
  Fireeye cracked hashes https://github.com/fireeye/sunburst_countermeasures/blob/main/fnv1a_xor_hashes.txt 

Example: 

  brutesunburst.exe AAAA

	BRUTESUNBURST HASHES =================
	>>>msmpeng 5183687599225757871
	>>>sense 16335643316870329598
	Pattern A or O eg. AAAA0
	Pattern:AAAA
	>>>cavp 17204844226884380288
	>>>date 16066522799090129502
	>>>dnsd 13316211011159594063
	>>>egui 607197993339007484
	>>>ekrn 3200333496547938354
	>>>epfw 17939405613729073960
	>>>fses 3413052607651207697
	>>>fsfw 3407972863931386250
	>>>fsma 3421213182954201407
	>>>fsms 3421197789791424393
	>>>fsni 3413886037471417852
	>>>idaq 14256853800858727521
	>>>ksde 17633734304611248415
	>>>peid 9531326785919727076
	>>>ppee 14710585101020280896
	>>>xagt 15695338751700748390
  
  
