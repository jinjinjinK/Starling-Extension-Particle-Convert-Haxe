# Starling-Extension-Particle-Convert-Haxe
Port of Starling Extension Particle 1.8 https://github.com/Gamua/Starling-Extension-Particle-System/tree/v1.8.x to Haxe

You will need to uncomment the line 147 at starling/utils/VertexData.hx

    public function append(data:VertexData):Void
    {
        //uncomment this next line, don't ask me why it is commented, I don't know :P
        mRawData.fixed = false;
