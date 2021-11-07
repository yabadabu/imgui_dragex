# imgui_dragex
Imgui::DragFloat and ImGui::DragInt with runtime customizable speed with the middle mouse button. Totally inspired in Houdini UI.

    static int ival = 100;
    ImGui::DragIntEx("Int value", &ival, 1, 0, INT_MAX );

![SampleIntegers](sample.gif)

    static float fval = 100;
    ImGui::DragFloatEx("float value", &fval, 1, -FLT_MAX, FLT_MAX);

![SampleFloats](sample_floats.gif)

# Integration

    Drop the two files inside the imgui folder in your imgui installation
    Add #include "imgui/imgui_drag_ex.h" in your source
    Change ImGui::DragInt to ImGui::DragIntEx (same for DragFloat)
    Replace the 3rd argument speed value to 1

