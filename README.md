## Note - Page Rank

* Self-rank is not accurate, let's involve everyone to rank

	####1. Quantity: 
	More important websites are likely yo reveive more links from other websites
	####2. Quality: 
	Website with higher PageRank will pass higher weight
	
	####3. Search History
	...
	
* 初始平等，数量 => 质量
* Transition Matrix
* Spider Traps{1,0,0,0}, Dead Ends{0,0,0,0}
	####* Teleporting 
	####* PR(N) = (1 - β) * PR(N-1) * Transition Matrix + β * PR(0)
	β = 重新选择网页概率(0.2左右)