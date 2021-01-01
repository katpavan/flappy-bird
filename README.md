http://www.lessmilk.com/tutorial/flappy-bird-phaser-1

idea for multiplayer

	one user flaps

	one user shoots

this.topPipes = this.physics.add.group({ key: 'pipe', frame: 0, repeat: topNum, setXY: { x: 200, y: 100, stepY: 40 } });
	//The final part is setXY - this is used to set the position of the topNum+1 children the Group creates. Each child will be placed starting at x: 200, y: 100 and with a y step of 40. This means that the first child will be positioned at 200 x 100, the second one is 40 pixels on from that at 200 x 140, the third one is at 200 x 180, and so on. The 'step' values are a really handy way of spacing out a Groups children during creation. The value of 40 is chosen because it means all topNum+1 children will be perfectly spaced out on the screen.