# Simple model to predict tumor size under Cheomeoterapy

I was diagnose witha a 12cm larbe Ewing's Arcoma in May/18. Since there, I'v been under cheomeoterapby (VDC+IE every 14days) and I got two new MRIs that showed significand and non-linear reduction in my tumor size.

Between a discussion on how many chemeos cycles I should go by before starting the Radioterapy, I'm got curious in the probable size of my tumor during the next cycles.

This simple model tries to predic the size of my tumor after the end of each chemoeteraphy cycle. Once cyle last for 4weeks, I'm assuming it to be one month. The only assumption I made is that the tumor reduction will follow a sigmoid curve, saturating around a tumor of size 0 (100% of reduction).

Once I have new MRI data I'll test the model.
