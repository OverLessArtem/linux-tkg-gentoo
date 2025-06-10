# linux-tkg-gentoo-openrc 🐧

🚀 A fork of the [linux-tkg](https://github.com/Frogging-Family/linux-tkg) project, tailored for Gentoo Linux with full OpenRC support. This repository enhances the original linux-tkg build system to deliver a high-performance, customizable Linux kernel optimized for Gentoo users who prefer OpenRC over systemd.

---

## 🇷🇺 RUS

### Описание
Этот форк проекта linux-tkg создан для обеспечения **полноценной поддержки Gentoo Linux с OpenRC**. Мы адаптировали систему сборки ядра, чтобы она идеально работала в экосистеме Gentoo, сохраняя все преимущества linux-tkg: производительность, гибкость и оптимизации для игр и десктопов. 🎮💻

### Что сделано:
- 🛠 **Поддержка OpenRC**: Заменены конфигурации Arch Linux на Gentoo-специфичные, обеспечивая полную совместимость с OpenRC вместо systemd.
- ⚙️ **Оптимизированный `customization.cfg`**: Настроен для Gentoo с использованием самой стабильной и производительной версии ядра, протестированной для OpenRC.
- 🚀 **Улучшения производительности**: Сохранены все патчи и оптимизации linux-tkg (Zen, Fsync, NTsync, Futex2 и др.) для гейминга и десктопного использования.
- 📦 **Упрощённая сборка**: Скрипты адаптированы для создания Gentoo-совместимых пакетов с минимальными усилиями.

### Для кого этот форк?
- Пользователей Gentoo, предпочитающих OpenRC.
- Геймеров и энтузиастов, желающих выжать максимум из ядра с минимальными задержками. 🎲
- Тех, кто хочет гибко настраивать ядро под свои нужды.

### Установка
1. Клонируйте репозиторий: `git clone https://github.com/your-username/linux-tkg-gentoo-openrc.git`
2. Настройте `customization.cfg` под ваши нужды (версия ядра и патчи уже оптимизированы для Gentoo).
3. Выполните сборку: `make && make install` (или используйте Gentoo-специфичные команды для установки ядра).
4. Обновите ваш загрузчик (например, GRUB) и наслаждайтесь! 🚀

---

## 🇬🇧 ENG

### Description
This fork of the [linux-tkg](https://github.com/Frogging-Family/linux-tkg) project is designed to provide **full support for Gentoo Linux with OpenRC**. It adapts the linux-tkg build system to seamlessly integrate with the Gentoo ecosystem, preserving the performance and flexibility of linux-tkg for gaming and desktop workloads. 🎮💻

### What's Changed:
- 🛠 **OpenRC Support**: Replaced Arch Linux configurations with Gentoo-specific ones, ensuring full compatibility with OpenRC instead of systemd.
- ⚙️ **Optimized `customization.cfg`**: Configured for Gentoo with the most stable and performant kernel version tested for OpenRC.
- 🚀 **Performance Enhancements**: Retains all linux-tkg patches and optimizations (Zen, Fsync, NTsync, Futex2, etc.) for gaming and desktop use.
- 📦 **Streamlined Build Process**: Scripts adapted to generate Gentoo-compatible packages with minimal effort.

### Who Is This For?
- Gentoo users who prefer OpenRC.
- Gamers and enthusiasts seeking a low-latency, high-performance kernel. 🎲
- Those who want a customizable kernel tailored to their needs.

### Installation
1. Clone the repository: `git clone https://github.com/your-username/linux-tkg-gentoo-openrc.git`
2. Customize `customization.cfg` as needed (kernel version and patches are pre-optimized for Gentoo).
3. Build the kernel: `make && make install` (or use Gentoo-specific commands for kernel installation).
4. Update your bootloader (e.g., GRUB) and enjoy! 🚀

---

🌟 **Contribute**: Feel free to submit issues or pull requests to improve this fork!  
📬 **Contact**: Reach out via GitHub for support or suggestions.