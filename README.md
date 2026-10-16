# infedge
本方案以 RK3588 为硬件底座，打通全链路零拷贝、硬件加速、EGL 绘制与硬件绘制管线；集成 AI 自动识别、文本叠加、传统动画、3D 动态渲染及最新格式支持；通过 C++ WebRTC 实现免二次编码，WebRTC 层采用 Rust + Mediasoup，整体技术栈为 Rust + C++ + Vue。方案可广泛应用于各类直播实时绘制场景，实现超低延迟；在网络波动下支持自动跳帧；并针对嵌入式环境提供覆盖发热控制、死机防护、异常重启恢复与多路并发的项目级解决方案。


Built on the RK3588 hardware foundation, this solution enables end-to-end zero-copy, hardware acceleration, and EGL/hardware rendering. It integrates AI-powered automatic recognition, text overlay, traditional animation, dynamic 3D rendering, and support for the latest formats. The media pipeline uses C++ WebRTC with no re-encoding, a Rust + Mediasoup WebRTC layer, and an overall Rust + C++ + Vue technology stack. Designed for real-time rendering across various live streaming scenarios, it delivers ultra-low latency, automatic frame dropping under network fluctuations, and project-level solutions for embedded thermal management, crash handling, restart recovery, and multi-channel concurrency.
