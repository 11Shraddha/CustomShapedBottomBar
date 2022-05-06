# CustomShapedBottomBar
Custom Shaped Bottom Navigation Bar in Flutter


<img width="386" alt="Screenshot 2022-05-06 at 5 52 32 PM" src="https://user-images.githubusercontent.com/59359564/167130441-d372e344-5d3f-4284-9cd8-6f0e91cf031d.png">


**Usage: **

Add CustomPaint Widget to use this Painter class like this: 

            Container(
              height: 200,
              width: 400,
              padding: const EdgeInsets.only(top: 80.0),
              child: CustomPaint(
                painter: ProfileCardPainter(
                    color: AppColors.themeGoldColor, avatarRadius: 30), //3
              ),
            )
