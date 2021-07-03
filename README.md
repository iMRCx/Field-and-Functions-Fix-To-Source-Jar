# Field-and-Functions-Fix-To-Source-Jar
The meaning of the "fields and functions" when you decompile a .jar in the Source Code
Imagine that you decompile a .jar in the "source code" and when trying to edit the SC, it votes for a function error. Use the files to translate the functions for Forge and Fabric
(EXAMPLE)
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

public static void dbb(AxisAlignedBB abb, float r, float g, float b) {
        float a = 0.25f;
        Tessellator ts = Tessellator.func_178181_a();
        WorldRenderer vb = ts.func_178180_c();
        vb.func_181668_a(7, DefaultVertexFormats.field_181706_f);
        vb.func_181662_b(abb.minX, abb.minY, abb.minZ).func_181666_a(r, g, b, a).func_181675_d();
        vb.func_181662_b(abb.minX, abb.maxY, abb.minZ).func_181666_a(r, g, b, a).func_181675_d();
        vb.func_181662_b(abb.maxX, abb.minY, abb.minZ).func_181666_a(r, g, b, a).func_181675_d();
        vb.func_181662_b(abb.maxX, abb.maxY, abb.minZ).func_181666_a(r, g, b, a).func_181675_d();
        vb.func_181662_b(abb.maxX, abb.minY, abb.maxZ).func_181666_a(r, g, b, a).func_181675_d();
        vb.func_181662_b(abb.maxX, abb.maxY, abb.maxZ).func_181666_a(r, g, b, a).func_181675_d();
        vb.func_181662_b(abb.minX, abb.minY, abb.maxZ).func_181666_a(r, g, b, a).func_181675_d();
        vb.func_181662_b(abb.minX, abb.maxY, abb.maxZ).func_181666_a(r, g, b, a).func_181675_d();
        ts.draw();
        vb.func_181668_a(7, DefaultVertexFormats.field_181706_f);
        vb.func_181662_b(abb.maxX, abb.maxY, abb.minZ).func_181666_a(r, g, b, a).func_181675_d();
        vb.func_181662_b(abb.maxX, abb.minY, abb.minZ).func_181666_a(r, g, b, a).func_181675_d();
        vb.func_181662_b(abb.minX, abb.maxY, abb.minZ).func_181666_a(r, g, b, a).func_181675_d();
        vb.func_181662_b(abb.minX, abb.minY, abb.minZ).func_181666_a(r, g, b, a).func_181675_d();
        vb.func_181662_b(abb.minX, abb.maxY, abb.maxZ).func_181666_a(r, g, b, a).func_181675_d();
        vb.func_181662_b(abb.minX, abb.minY, abb.maxZ).func_181666_a(r, g, b, a).func_181675_d();
        vb.func_181662_b(abb.maxX, abb.maxY, abb.maxZ).func_181666_a(r, g, b, a).func_181675_d();
        vb.func_181662_b(abb.maxX, abb.minY, abb.maxZ).func_181666_a(r, g, b, a).func_181675_d();
        ts.draw();
