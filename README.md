# Chapter-4
第四讲 复杂应用组件 Handler机制、多线程、 自定义View

todo部分代码补全如下：
// todo 每一秒刷新一次，让指针动起来  
postInvalidateDelayed(1000);

// todo 画分针  
drawPointer(canvas, 1, nowMinutes);  
     
// todo 画分针，设置分针的颜色  
degree = value * UNIT_DEGREE;  
mNeedlePaint.setColor(Color.BLUE);  
pointerHeadXY = getPointerHeadXY(MINUTE_POINTER_LENGTH, degree);  
