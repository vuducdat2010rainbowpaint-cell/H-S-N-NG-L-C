<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hồ sơ Năng Lực - Công Ty TNHH Yung Chi Paint & Varnish MFG (VN)</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Segoe UI', system-ui, sans-serif;
            background: linear-gradient(135deg, #f0f9ff 0%, #e0f2fe 100%);
            min-height: 100vh;
        }
        .fade-in {
            opacity: 0;
            animation: fadeIn 0.8s ease-in-out forwards;
        }
        @keyframes fadeIn {
            from { 
                opacity: 0; 
                transform: translateY(20px); 
            }
            to { 
                opacity: 1; 
                transform: translateY(0); 
            }
        }
        .hover-scale {
            transition: all 0.3s ease;
        }
        .hover-scale:hover {
            transform: scale(1.02);
            box-shadow: 0 10px 25px -5px rgba(0, 0, 0, 0.1), 0 10px 10px -5px rgba(0, 0, 0, 0.04);
        }
        .stats-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
            margin: 2rem 0;
        }
        .production-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 1.5rem;
            margin: 2rem 0;
        }
        .team-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 1.5rem;
            margin: 2rem 0;
        }
        .contact-flex {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 1rem;
            margin: 2rem 0;
        }
        .card {
            background: white;
            border-radius: 1rem;
            padding: 2rem;
            box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1), 0 2px 4px -1px rgba(0, 0, 0, 0.06);
        }
        .gradient-bg {
            background: linear-gradient(135deg, #2563eb 0%, #4f46e5 100%);
        }
        @media (max-width: 768px) {
            .production-grid {
                grid-template-columns: 1fr;
            }
            .team-grid {
                grid-template-columns: repeat(2, 1fr);
            }
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header style="background: white; box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1);">
        <div style="max-width: 1200px; margin: 0 auto; padding: 2rem 1.5rem;">
            <h1 style="font-size: 2.25rem; font-weight: bold; color: #1f2937; text-align: center; margin-bottom: 0.5rem;">
                Năng Lực Sản Xuất
            </h1>
            <p style="font-size: 1.25rem; color: #4b5563; text-align: center;">
                Công Ty TNHH Yung Chi Paint & Varnish MFG (VN)
            </p>
        </div>
    </header>
    <main style="max-width: 1200px; margin: 0 auto; padding: 3rem 1.5rem;">
        <!-- Tổng quan -->
        <section class="fade-in" style="margin-bottom: 4rem;">
            <div class="card">
                <h2 style="font-size: 1.875rem; font-weight: bold; color: #1f2937; margin-bottom: 1.5rem; display: flex; align-items: center;">
                    <i class="fas fa-chart-line" style="color: #2563eb; margin-right: 0.75rem;"></i>
                    Tổng Quan Năng Lực
                </h2>
                <div class="stats-grid">
                    <div class="hover-scale" style="text-align: center; padding: 1.5rem; background: #dbeafe; border-radius: 0.75rem;">
                        <div style="font-size: 2.25rem; font-weight: bold; color: #2563eb; margin-bottom: 0.5rem;">15+</div>
                        <div style="color: #374151; font-weight: 500;">Năm Kinh Nghiệm</div>
                    </div>
                    <div class="hover-scale" style="text-align: center; padding: 1.5rem; background: #dcfce7; border-radius: 0.75rem;">
                        <div style="font-size: 2.25rem; font-weight: bold; color: #16a34a; margin-bottom: 0.5rem;">500,000</div>
                        <div style="color: #374151; font-weight: 500;">Sản Phẩm/Năm</div>
                    </div>
                    <div class="hover-scale" style="text-align: center; padding: 1.5rem; background: #f3e8ff; border-radius: 0.75rem;">
                        <div style="font-size: 2.25rem; font-weight: bold; color: #9333ea; margin-bottom: 0.5rem;">99.6%</div>
                        <div style="color: #374151; font-weight: 500;">Chất Lượng Đạt Chuẩn</div>
                    </div>
                </div>
            </div>
        </section>
        <!-- Dây chuyền sản xuất -->
        <section class="fade-in" style="margin-bottom: 4rem;">
            <div class="card">
                <h2 style="font-size: 1.875rem; font-weight: bold; color: #1f2937; margin-bottom: 2rem; display: flex; align-items: center;">
                    <i class="fas fa-industry" style="color: #ea580c; margin-right: 0.75rem;"></i>
                    Dây Chuyền Sản Xuất
                </h2>
                <div class="production-grid">
                    <!-- Dây chuyền A -->
                    <div class="hover-scale" style="background: linear-gradient(135deg, #fef2f2 0%, #fee2e2 100%); padding: 1.5rem; border-radius: 0.75rem;">
                        <div style="color: #dc2626; font-size: 1.875rem; margin-bottom: 1rem;">
                            <i class="fas fa-factory"></i>
                        </div>
                        <h3 style="font-weight: bold; color: #1f2937; margin-bottom: 0.5rem;">Dây Chuyền A</h3>
                        <p style="color: #6b7280; font-size: 0.875rem; margin-bottom: 0.75rem;">Sản xuất sơn dầu-nước</p>
                        <div style="font-size: 0.875rem;">
                            <div style="display: flex; justify-content: space-between; margin-bottom: 0.25rem;">
                                <span>Công suất:</span>
                                <span style="font-weight: 500;">15,000/tháng</span>
                            </div>
                            <div style="display: flex; justify-content: space-between;">
                                <span>Trạng thái:</span>
                                <span style="color: #16a34a; font-weight: 500;">Hoạt động</span>
                            </div>
                        </div>
                    </div>
                    <!-- Dây chuyền B -->
                    <div class="hover-scale" style="background: linear-gradient(135deg, #eff6ff 0%, #dbeafe 100%); padding: 1.5rem; border-radius: 0.75rem;">
                        <div style="color: #2563eb; font-size: 1.875rem; margin-bottom: 1rem;">
                            <i class="fas fa-cogs"></i>
                        </div>
                        <h3 style="font-weight: bold; color: #1f2937; margin-bottom: 0.5rem;">Dây Chuyền B</h3>
                        <p style="color: #6b7280; font-size: 0.875rem; margin-bottom: 0.75rem;">Sản phẩm hoàn thiện</p>
                        <div style="font-size: 0.875rem;">
                            <div style="display: flex; justify-content: space-between; margin-bottom: 0.25rem;">
                                <span>Công suất:</span>
                                <span style="font-weight: 500;">15,000/tháng</span>
                            </div>
                            <div style="display: flex; justify-content: space-between;">
                                <span>Trạng thái:</span>
                                <span style="color: #16a34a; font-weight: 500;">Hoạt động</span>
                            </div>
                        </div>
                    </div>
                    <!-- Dây chuyền C -->
                    <div class="hover-scale" style="background: linear-gradient(135deg, #f0fdf4 0%, #dcfce7 100%); padding: 1.5rem; border-radius: 0.75rem;">
                        <div style="color: #16a34a; font-size: 1.875rem; margin-bottom: 1rem;">
                            <i class="fas fa-box"></i>
                        </div>
                        <h3 style="font-weight: bold; color: #1f2937; margin-bottom: 0.5rem;">Dây Chuyền C</h3>
                        <p style="color: #6b7280; font-size: 0.875rem; margin-bottom: 0.75rem;">Đóng gói và kiểm tra chất lượng</p>
                        <div style="font-size: 0.875rem;">
                            <div style="display: flex; justify-content: space-between; margin-bottom: 0.25rem;">
                                <span>Công suất:</span>
                                <span style="font-weight: 500;">25,000/tháng</span>
                            </div>
                            <div style="display: flex; justify-content: space-between;">
                                <span>Trạng thái:</span>
                                <span style="color: #16a34a; font-weight: 500;">Hoạt động</span>
                            </div>
                        </div>
                    </div>
                    <!-- Dây chuyền D -->
                    <div class="hover-scale" style="background: linear-gradient(135deg, #faf5ff 0%, #f3e8ff 100%); padding: 1.5rem; border-radius: 0.75rem;">
                        <div style="color: #9333ea; font-size: 1.875rem; margin-bottom: 1rem;">
                            <i class="fas fa-tools"></i>
                        </div>
                        <h3 style="font-weight: bold; color: #1f2937; margin-bottom: 0.5rem;">Dây Chuyền D</h3>
                        <p style="color: #6b7280; font-size: 0.875rem; margin-bottom: 0.75rem;">Bảo trì và sửa chữa</p>
                        <div style="font-size: 0.875rem;">
                            <div style="display: flex; justify-content: space-between; margin-bottom: 0.25rem;">
                                <span>Công suất:</span>
                                <span style="font-weight: 500;">5,000/tháng</span>
                            </div>
                            <div style="display: flex; justify-content: space-between;">
                                <span>Trạng thái:</span>
                                <span style="color: #ca8a04; font-weight: 500;">Bảo trì</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <!-- Thiết bị và công nghệ -->
        <section class="fade-in" style="margin-bottom: 4rem;">
            <div class="card">
                <h2 style="font-size: 1.875rem; font-weight: bold; color: #1f2937; margin-bottom: 2rem; display: flex; align-items: center;">
                    <i class="fas fa-microchip" style="color: #4f46e5; margin-right: 0.75rem;"></i>
                    Thiết Bị & Công Nghệ
                </h2>
                <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 2rem;">
                    <div>
                        <h3 style="font-size: 1.25rem; font-weight: bold; color: #1f2937; margin-bottom: 1rem;">Máy móc hiện đại</h3>
                        <ul style="space-y: 0.75rem;">
                            <li style="display: flex; align-items: center; margin-bottom: 0.75rem;">
                                <span style="width: 0.5rem; height: 0.5rem; background: #16a34a; border-radius: 50%; margin-right: 0.75rem;"></span>
                                <span>Máy khuấy tự động - 10 bộ</span>
                            </li>
                            <li style="display: flex; align-items: center; margin-bottom: 0.75rem;">
                                <span style="width: 0.5rem; height: 0.5rem; background: #16a34a; border-radius: 50%; margin-right: 0.75rem;"></span>
                                <span>Robot lắp ráp - 8 bộ</span>
                            </li>
                            <li style="display: flex; align-items: center; margin-bottom: 0.75rem;">
                                <span style="width: 0.5rem; height: 0.5rem; background: #16a34a; border-radius: 50%; margin-right: 0.75rem;"></span>
                                <span>Hệ thống kiểm tra chất lượng tự động</span>
                            </li>
                            <li style="display: flex; align-items: center;">
                                <span style="width: 0.5rem; height: 0.5rem; background: #16a34a; border-radius: 50%; margin-right: 0.75rem;"></span>
                                <span>Dây chuyền đóng gói thông minh</span>
                            </li>
                        </ul>
                    </div>
                    <div>
                        <h3 style="font-size: 1.25rem; font-weight: bold; color: #1f2937; margin-bottom: 1rem;">Chứng nhận & Tiêu chuẩn</h3>
                        <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 1rem;">
                            <div style="background: #dbeafe; padding: 1rem; border-radius: 0.5rem; text-align: center;">
                                <div style="font-size: 1.5rem; margin-bottom: 0.5rem;"><i class="fas fa-trophy"></i></div>
                                <div style="font-weight: 500; font-size: 0.875rem;">ISO 9001:2015</div>
                            </div>
                            <div style="background: #dcfce7; padding: 1rem; border-radius: 0.5rem; text-align: center;">
                                <div style="font-size: 1.5rem; margin-bottom: 0.5rem;"><i class="fas fa-leaf"></i></div>
                                <div style="font-weight: 500; font-size: 0.875rem;">ISO 14001:2015</div>
                            </div>
                            <div style="background: #f3e8ff; padding: 1rem; border-radius: 0.5rem; text-align: center;">
                                <div style="font-size: 1.5rem; margin-bottom: 0.5rem;"><i class="fas fa-heartbeat"></i></div>
                                <div style="font-weight: 500; font-size: 0.875rem;">ISO 45001:2018</div>
                            </div>
                            <div style="background: #ffedd5; padding: 1rem; border-radius: 0.5rem; text-align: center;">
                                <div style="font-size: 1.5rem; margin-bottom: 0.5rem;"><i class="fas fa-star"></i></div>
                                <div style="font-weight: 500; font-size: 0.875rem;">CE Marking</div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <!-- Nhân lực -->
        <section class="fade-in" style="margin-bottom: 4rem;">
            <div class="card">
                <h2 style="font-size: 1.875rem; font-weight: bold; color: #1f2937; margin-bottom: 2rem; display: flex; align-items: center;">
                    <i class="fas fa-users" style="color: #0d9488; margin-right: 0.75rem;"></i>
                    Đội Ngũ Nhân Lực
                </h2>
                <div class="team-grid">
                    <div style="text-align: center; padding: 1.5rem; background: linear-gradient(135deg, #cffafe 0%, #a5f3fc 100%); border-radius: 0.75rem;">
                        <div style="font-size: 2.25rem; margin-bottom: 0.75rem;"><i class="fas fa-user-tie"></i></div>
                        <div style="font-size: 1.5rem; font-weight: bold; color: #0891b2; margin-bottom: 0.25rem;">20</div>
                        <div style="color: #4b5563; font-weight: 500;">Quản lý</div>
                    </div>
                    <div style="text-align: center; padding: 1.5rem; background: linear-gradient(135deg, #d1fae5 0%, #a7f3d0 100%); border-radius: 0.75rem;">
                        <div style="font-size: 2.25rem; margin-bottom: 0.75rem;"><i class="fas fa-user-cog"></i></div>
                        <div style="font-size: 1.5rem; font-weight: bold; color: #059669; margin-bottom: 0.25rem;">80</div>
                        <div style="color: #4b5563; font-weight: 500;">Kỹ thuật viên</div>
                    </div>
                    <div style="text-align: center; padding: 1.5rem; background: linear-gradient(135deg, #fef3c7 0%, #fde68a 100%); border-radius: 0.75rem;">
                        <div style="font-size: 2.25rem; margin-bottom: 0.75rem;"><i class="fas fa-hard-hat"></i></div>
                        <div style="font-size: 1.5rem; font-weight: bold; color: #d97706; margin-bottom: 0.25rem;">800</div>
                        <div style="color: #4b5563; font-weight: 500;">Công nhân</div>
                    </div>
                    <div style="text-align: center; padding: 1.5rem; background: linear-gradient(135deg, #ffe4e6 0%, #fecdd3 100%); border-radius: 0.75rem;">
                        <div style="font-size: 2.25rem; margin-bottom: 0.75rem;"><i class="fas fa-flask"></i></div>
                        <div style="font-size: 1.5rem; font-weight: bold; color: #e11d48; margin-bottom: 0.25rem;">20</div>
                        <div style="color: #4b5563; font-weight: 500;">R&D</div>
                    </div>
                </div>
            </div>
        </section>
        <!-- Liên hệ -->
        <section class="fade-in">
            <div class="gradient-bg" style="border-radius: 1rem; box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.1); padding: 2rem; color: white; text-align: center;">
                <h2 style="font-size: 1.875rem; font-weight: bold; margin-bottom: 1rem;">Liên Hệ Hợp Tác</h2>
                <p style="font-size: 1.25rem; margin-bottom: 1.5rem; opacity: 0.9;">Sẵn sàng đáp ứng mọi nhu cầu sản xuất của quý khách hàng</p>
                <div class="contact-flex">
                    <div style="background: rgba(255, 255, 255, 0.2); padding: 0.75rem 1.5rem; border-radius: 0.5rem;">
                        <div style="font-weight: 500;"><i class="fas fa-phone" style="margin-right: 0.5rem;"></i>Hotline: 0966-337-196</div>
                    </div>
                    <div style="background: rgba(255, 255, 255, 0.2); padding: 0.75rem 1.5rem; border-radius: 0.5rem;">
                        <div style="font-weight: 500;"><i class="fas fa-envelope" style="margin-right: 0.5rem;"></i>Email: vuducdat2010.rainbowpaint@gmail.com</div>
                    </div>
                    <div style="background: rgba(255, 255, 255, 0.2); padding: 0.75rem 1.5rem; border-radius: 0.5rem;">
                        <div style="font-weight: 500;"><i class="fas fa-map-marker-alt" style="margin-right: 0.5rem;"></i>Địa chỉ: Lô 219, KCN AMATA, Tỉnh Đồng Nai</div>
                    </div>
                </div>
            </div>
        </section>
    </main>
    <footer style="background: #1f2937; color: white; padding: 2rem 0; margin-top: 4rem;">
        <div style="max-width: 1200px; margin: 0 auto; padding: 0 1.5rem; text-align: center;">
            <p>&copy; 2024 Công Ty TNHH Yung Chi Paint & Varnish MFG (VN).</p>
        </div>
    </footer>
    <script>
        // Add fade-in animation on scroll
        document.addEventListener('DOMContentLoaded', function() {
            const fadeElements = document.querySelectorAll('.fade-in');
            const fadeInOnScroll = function() {
                fadeElements.forEach(element => {
                    const elementTop = element.getBoundingClientRect().top;
                    const elementVisible = 150;
                    if (elementTop < window.innerHeight - elementVisible) {
                        element.style.opacity = "1";
                        element.style.transform = "translateY(0)";
                    }
                });
            };
            // Initial check
            fadeInOnScroll();
            
            // Check on scroll
            window.addEventListener('scroll', fadeInOnScroll);
        });
    </script>
</body>
</html>
