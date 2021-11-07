# imgui_dragex
Imgui::DragFloat and ImGui::DragInt with customizable speed with the middle mouse button. Totally inspired in Houdini.

    static int ival = 100;
    ImGui::DragIntEx("Int value", &ival, 1, 0, INT_MAX );

![Sample Frame](sample.gif)