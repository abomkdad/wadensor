<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Warehouse Map</title>
    <style>
        body, html {
            margin: 0;
            padding: 0;
            height: 100%;
            overflow: hidden;
        }
        .min-h-screen {
            min-height: 100vh;
        }
        .text-white {
            color: white;
        }
        .p-0 {
            padding: 0;
        }
        .bg-cover {
            background-size: cover;
        }
        .bg-center {
            background-position: center;
        }
        .relative {
            position: relative;
        }
        .absolute {
            position: absolute;
        }
        .cursor-pointer {
            cursor: pointer;
        }
        .rounded-full {
            border-radius: 50%;
        }
        .border {
            border: 1px solid;
        }
        .border-white {
            border-color: white;
        }
        .w-8 {
            width: 2rem;
        }
        .h-8 {
            height: 2rem;
        }
        .bg-white {
            background-color: white;
        }
        .bg-opacity-75 {
            background-color: rgba(255, 255, 255, 0.75);
        }
        .rounded-md {
            border-radius: 0.375rem;
        }
        .p-2 {
            padding: 0.5rem;
        }
        .text-black {
            color: black;
        }
        .mt-1 {
            margin-top: 0.25rem;
        }
        .border-gray-300 {
            border-color: #d1d5db;
        }
        .shadow-lg {
            box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1), 0 4px 6px -2px rgba(0, 0, 0, 0.05);
        }
        .hover\:bg-gray-100:hover {
            background-color: #f3f4f6;
        }
        .z-10 {
            z-index: 10;
        }
        .z-20 {
            z-index: 20;
        }
        @keyframes pulse {
            0%, 100% {
                opacity: 1;
            }
            50% {
                opacity: 0.5;
            }
        }
        .animate-pulse {
            animation: pulse 2s cubic-bezier(0.4, 0, 0.6, 1) infinite;
        }
    </style>
</head>
<body>
    <div id="root"></div>

    <script crossorigin src="https://unpkg.com/react@18/umd/react.development.js"></script>
    <script crossorigin src="https://unpkg.com/react-dom@18/umd/react-dom.development.js"></script>

    <script src="https://unpkg.com/@babel/standalone/babel.min.js"></script>

    <script type="text/babel">
        const WarehouseMap = () => {
          const [selectedProduct, setSelectedProduct] = React.useState(null);
          const [draggingProduct, setDraggingProduct] = React.useState(null);
          const [isDragging, setIsDragging] = React.useState(false);
          const [products, setProducts] = React.useState([
    {
        "ProductName": "Description",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/A101.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "A102",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/A102.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "A104",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/A104.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "A105",
        "Image Link": "https://madperfume.co.il/upload/05-2024/product/A.105.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "A113",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/A113.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "A114",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/A114.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "A115",
        "Image Link": "https://madperfume.co.il/upload/03-2025/product/IMG_6217.JPG",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "B102",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/WhatsApp Image 2023-07-19 at 02.49.20.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "B104",
        "Image Link": "https://madperfume.co.il/upload/03-2025/product/PHOTO-2023-07-19-05-19-58%202.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "B106",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/B106.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "B107",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/WhatsApp Image 2023-07-19 at 02.50.11.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "B108",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/B.108.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "B110",
        "Image Link": "https://madperfume.co.il/upload/08-2024/product/TRT.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "C101",
        "Image Link": "https://madperfume.co.il/upload/03-2025/product/67e67d1c49809.png",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "C108",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/WhatsApp Image 2023-07-19 at 02.50.21.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "C109",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/WhatsApp Image 2023-07-19 at 02.50.39.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "D.110",
        "Image Link": "https://madperfume.co.il/upload/08-2024/product/FRFF.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "D102",
        "Image Link": "https://madperfume.co.il/upload/02-2025/product/67bd94089bf2a.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "E104",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/E104.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "F101",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/WhatsApp Image 2023-07-19 at 02.50.52.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "G101",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/G101.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "G103",
        "Image Link": "https://madperfume.co.il/upload/11-2024/product/3 (1).jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "H101",
        "Image Link": "https://static.ticimax.cloud/cdn-cgi/image/width=615,quality=85,format=webp/51735/uploads/urunresimleri/buyuk/mad-h101-selective-100-ml-erkek-parfum-ba-4d3.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "H106",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/H106.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "I101",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/WhatsApp Image 2023-07-19 at 02.51.08.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "I102",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/i102.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "I104",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/WhatsApp Image 2023-07-19 at 02.51.24.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "J101",
        "Image Link": "https://madperfume.co.il/upload/03-2025/product/IMG_6162.JPG",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "J102",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/WhatsApp Image 2023-07-19 at 02.51.49.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "J103",
        "Image Link": "https://madperfume.co.il/upload/03-2025/product/J103.png",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "J104",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/J104.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "J105",
        "Image Link": "https://d3m9l0v76dty0.cloudfront.net/system/photos/13746596/large/2548fb6107f5db62e04db084d3342b46.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "J107",
        "Image Link": "https://madperfume.co.il/upload/08-2024/product/66b89aea5facd.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "J109",
        "Image Link": "https://madperfume.co.il/upload/08-2024/product/GTYY.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "K101",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/K101.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "L101",
        "Image Link": "https://madperfume.co.il/upload/05-2024/product/SANTAL 33.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "L102",
        "Image Link": "https://madperfume.co.il/upload/01-2024/product/L102.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "L103",
        "Image Link": "https://madperfume.co.il/upload/05-2024/product/6639537753986.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "L103 EXTRA",
        "Image Link": "https://madperfume.co.il/upload/11-2024/product/2.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "L105",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/WhatsApp Image 2023-07-19 at 02.52.23.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "L106",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/L106.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "P101",
        "Image Link": "https://madperfume.co.il/upload/05-2024/product/PARFUMS DE MARLY PEGASUS.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "P102",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/WhatsApp Image 2023-07-19 at 02.52.51.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "P103",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/WhatsApp Image 2023-07-19 at 02.53.06.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "P104",
        "Image Link": "https://madperfume.co.il/upload/05-2024/product/6636b3596b315.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "P105",
        "Image Link": "https://madperfume.co.il/upload/08-2024/product/444.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "gift",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/WhatsApp Image 2023-07-19 at 02.53.17.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Q102",
        "Image Link": "https://madperfume.co.il/upload/03-2025/product/67c4309ac6954.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Q105",
        "Image Link": "https://madperfume.co.il/upload/03-2025/product/WhatsApp%20Image%202023-07-19%20at%2002.53.27-450px.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Q107",
        "Image Link": "https://madperfume.co.il/upload/03-2025/product/IMG_6210.JPG",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Q109",
        "Image Link": "https://madperfume.co.il/upload/03-2025/product/IMG_6180.JPG",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Q112",
        "Image Link": "https://madperfume.co.il/upload/08-2024/product/Untitled-1YUU.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "gift",
        "Image Link": "https://madperfume.co.il/upload/08-2024/product/Untitled-FFF.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "gift",
        "Image Link": "https://madperfume.co.il/upload/08-2024/product/WEEER.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "gift",
        "Image Link": "https://madperfume.co.il/upload/08-2024/product/Untitled-1PLP.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "gift",
        "Image Link": "https://madperfume.co.il/upload/08-2024/product/66b8954fc1a9d.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "gift",
        "Image Link": "https://madperfume.co.il/upload/08-2024/product/III.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "gift",
        "Image Link": "https://madperfume.co.il/upload/11-2024/product/8.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "gift",
        "Image Link": "https://madperfume.co.il/upload/11-2024/product/5.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "gift",
        "Image Link": "https://madperfume.co.il/upload/11-2024/product/7.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "gift",
        "Image Link": "https://madperfume.co.il/upload/11-2024/product/6.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "gift",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/R103.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "S102",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/S102.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "T102",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/T102.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "T106 או Q108",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/WhatsApp Image 2023-07-19 at 02.54.12.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "T107",
        "Image Link": "https://madperfume.co.il/upload/08-2024/product/DFF.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "T109",
        "Image Link": "https://madperfume.co.il/upload/05-2024/product/TOMAS 4.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "T109 EXTRA",
        "Image Link": "https://madperfume.co.il/upload/11-2024/product/4.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "V102",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/WhatsApp Image 2023-07-19 at 02.54.25.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "W111",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/WhatsApp Image 2023-07-19 at 02.54.55.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "W120",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/WhatsApp Image 2023-07-19 at 02.55.09.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "W122",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/W122.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "W126",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/WhatsApp Image 2023-07-19 at 02.55.20.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "W128",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/WhatsApp Image 2023-07-19 at 02.55.30.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "W129",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/w129.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "W133",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/W133.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "W139",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/WhatsApp Image 2023-07-19 at 02.55.40.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "W143",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/WhatsApp Image 2023-07-19 at 02.55.50.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "W150",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/WhatsApp Image 2023-07-19 at 02.56.07.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "W158",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/w158 (1).jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "W160",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/WhatsApp Image 2023-07-19 at 02.56.17.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "W161",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/WhatsApp Image 2023-07-19 at 02.56.33.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "W163",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/000000 copy.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "W164",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/WhatsApp Image 2023-07-19 at 02.56.44.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "W170",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/W170.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "W171",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/000000 copy55.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "W172",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/WhatsApp Image 2023-07-19 at 02.51.49 copynjjjkk.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "W173",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/W173.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "W174",
        "Image Link": "https://madperfume.co.il/upload/03-2025/product/PHOTO-2023-07-19-05-20-22%205.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "W180",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/WhatsApp Image 2023-07-19 at 02.57.07.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "W181",
        "Image Link": "https://madperfume.co.il/upload/07-2024/product/668a79b38af9e.png",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "W183",
        "Image Link": "https://madperfume.co.il/upload/05-2024/product/CREED1.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "W183 Extra",
        "Image Link": "https://madperfume.co.il/upload/11-2024/product/1.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "W184",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/000000 333.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "W189",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/W189.jpeg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "W190",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/w190.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "W191",
        "Image Link": "https://madperfume.co.il/upload/05-2024/product/W191.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "W192",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/WhatsApp Image 2023-07-19 at 02.57.47.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "W198",
        "Image Link": "https://madperfume.co.il/upload/08-2024/product/WWW.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "x102",
        "Image Link": "https://madperfume.co.il/upload/05-2024/product/NAXOS.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Y101",
        "Image Link": "https://madperfume.co.il/upload/01-2024/product/Y101.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Y102",
        "Image Link": "https://madperfume.co.il/upload/03-2025/product/67e67a496135e.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "A104",
        "Image Link": "https://madperfume.co.il/upload/03-2025/product/MAD%20Perfume.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "A112",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/WhatsApp Image 2023-07-19 at 2.49.06 AM.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "A113",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/A113 (1).jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "A114",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/A114..jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "A117",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/WhatsApp Image 2023-07-19 at 2.48.26 AM.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "A118",
        "Image Link": "https://madperfume.co.il/upload/03-2025/product/WhatsApp%20Image%202023-07-19%20at%202.49.31%20AM.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "A120",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/A120.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "A121",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/WhatsApp Image 2023-07-19 at 2.49.45 AM.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "A122",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/WhatsApp Image 2023-07-19 at 2.50.06 AM.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "B103",
        "Image Link": "https://madperfume.co.il/upload/03-2025/product/IMG_6164.JPG",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "B105",
        "Image Link": "https://madperfume.co.il/upload/03-2025/product/67e6814457d4b.png",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "B106",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/6502c99017418.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "B110",
        "Image Link": "https://madperfume.ps/upload/08-2024/product/TRT.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "C119",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/C119.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "c120",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/WhatsApp Image 2023-07-19 at 2.50.36 AM (1).jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "C121",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/WhatsApp Image 2023-07-19 at 2.50.43 AM.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "C122",
        "Image Link": "https://madperfume.co.il/upload/11-2024/product/9.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "C123",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/C123.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "C126",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/WhatsApp Image 2023-07-19 at 2.51.05 AM.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "D104",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/WhatsApp Image 2023-07-19 at 2.51.23 AM.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "D114",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/WhatsApp Image 2023-07-19 at 2.51.48 AM.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "D117",
        "Image Link": "https://madperfume.co.il/upload/07-2024/product/IMG_6166 copy.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "gift",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/D119.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "D121",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/WhatsApp Image 2023-07-19 at 2.52.25 AM.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "E.117",
        "Image Link": "https://madperfume.co.il/upload/07-2024/product/668b98186d644.png",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "E101",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/WhatsApp Image 2023-07-19 at 2.52.47 AM.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "E104",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/E104 ..jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "G103",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/WhatsApp Image 2023-07-19 at 2.52.59 AM.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "G104",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/WhatsApp Image 2023-07-19 at 2.53.15 AM.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "G106",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/WhatsApp Image 2023-07-19 at 2.53.28 AM.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "G107",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/WhatsApp Image 2023-07-19 at 3.00.06 AM.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "G108",
        "Image Link": "https://madperfume.co.il/upload/02-2025/product/67b910d497a70.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "G109",
        "Image Link": "https://madperfume.co.il/upload/08-2024/product/UJY.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "gift",
        "Image Link": "https://madperfume.ps/upload/08-2024/product/RRRW3.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "gift",
        "Image Link": "https://madperfume.co.il/upload/08-2024/product/FGGBV.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "H103",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/WhatsApp Image 2023-07-19 at 2.53.39 AM.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "H104",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/H104.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "I102",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/I102..jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "J101",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/WhatsApp Image 2023-07-19 at 2.53.54 AM.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "J102",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/WhatsApp Image 2023-07-19 at 2.54.07 AM.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "J103",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/J103.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "J104 או Q103",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/WhatsApp Image 2023-07-19 at 3.00.17 AM.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "K101",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/K101 ..jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "L101",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/WhatsApp Image 2023-07-19 at 2.54.18 AM.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "L102",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/WhatsApp Image 2023-07-19 at 2.59.55 AM.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "L103",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/L103.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "L112",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/WhatsApp Image 2023-07-19 at 2.54.38 AM.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "M101",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/M101.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "M104",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/WhatsApp Image 2023-07-19 at 2.54.55 AM.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "N101",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/N101.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "N105",
        "Image Link": "https://madperfume.co.il/upload/04-2024/product/436204629_120210932116610029_2873960546412267218_n copy4.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "N106",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/N106.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "P101",
        "Image Link": "https://madperfume.co.il/upload/03-2025/product/67e5169fd2adc.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "P104",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/WhatsApp Image 2023-07-19 at 2.59.30 AM.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "P105",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/P105.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "P107",
        "Image Link": "https://madperfume.co.il/upload/03-2025/product/P107.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Q111",
        "Image Link": "https://madperfume.co.il/upload/05-2024/product/663953132053c.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Q117",
        "Image Link": "https://madperfume.co.il/upload/08-2024/product/R4T.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "R105",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/WhatsApp Image 2023-07-19 at 2.55.07 AM.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "R109",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/WhatsApp Image 2023-07-19 at 2.55.27 AM.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "R110",
        "Image Link": "https://madperfume.co.il/upload/11-2024/product/R110-IDX.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "S101",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/WhatsApp Image 2023-07-19 at 2.55.39 AM.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "S112",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/S112.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "T101",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/WhatsApp Image 2023-07-19 at 3.00.28 AM.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "T103 נשים או Q101",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/T 103.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "U101",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/U101.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "V101",
        "Image Link": "https://madperfume.co.il/upload/07-2024/product/IMG_6218 copy.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "V102",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/V102.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "V105",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/V105.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "V106",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/WhatsApp Image 2023-07-19 at 2.56.17 AM.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "V107",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/65024faa08d2b.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "V109",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/V109.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "V110",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/V110.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "V113",
        "Image Link": "https://madperfume.co.il/upload/01-2024/product/V113.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "V114",
        "Image Link": "https://madperfume.co.il/upload/08-2024/product/5.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "W101",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/W101.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "W113",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/W113.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "W125",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/W125.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "W144",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/w144.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "W150",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/WhatsApp Image 2023-07-19 at 2.57.11 AM.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "W152",
        "Image Link": "https://madperfume.co.il/upload/08-2024/product/555.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "W153",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/WhatsApp Image 2023-07-19 at 2.57.22 AM.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "W154",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/W154.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "W155",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/W155.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "W160",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/w163.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "W162",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/w162.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "W164",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/w164.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "W165",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/WhatsApp Image 2023-07-19 at 2.57.37 AM.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "W169",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/W169.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "W175",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/WhatsApp Image 2023-07-19 at 2.57.48 AM.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "W179",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/W179.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "W184",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/W184.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "W185",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/67a8a9a8ba31d5f908a0f4ba31904ec7.jpeg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "W190",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/W190..jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "W197",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/W197..jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "W201",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/WhatsApp Image 2023-07-19 at 2.58.44 AM.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "W203",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/WhatsApp Image 2023-07-19 at 2.58.55 AM.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "W208",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/W208.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "W209",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/W209..jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "W213",
        "Image Link": "https://madperfume.co.il/upload/03-2025/product/IMG_6139.JPG",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "W214",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/W214.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "W217",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/W217.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "W222",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/WhatsApp Image 2023-07-19 at 3.00.40 AM.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "W230",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/w230.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Y102",
        "Image Link": "https://d3m9l0v76dty0.cloudfront.net/system/photos/12935722/large/23004a847d708990c61a960f99930e13.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Y101",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/WhatsApp Image 2023-07-19 at 2.56.43 AM.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Z101",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/Z101.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Z102",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/Z102.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Bruno Casanova",
        "Image Link": "https://madperfume.co.il/upload/07-2024/product/668baae99f552.png",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Bruno Exotic",
        "Image Link": "https://madperfume.co.il/upload/07-2024/product/668bad0cde6b9.png",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Bruno Gold",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/bruno-gold.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Dependece",
        "Image Link": "https://madperfume.co.il/upload/11-2024/product/6745d8ead5670.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Deserto",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/deserto-100-ml-erkek-parfum100-ml-7-a663.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "DETOX",
        "Image Link": "https://madperfume.co.il/upload/03-2024/product/6603fdee65644.png",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Devil\\u0027s Trick",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/mad-devils-trick-100-ml-kadin-parfum10-4298-9.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Divine",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/divine.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Divine Tough",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/divine-tough.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "DRACO",
        "Image Link": "https://static.ticimax.cloud/cdn-cgi/image/width=540,quality=85,format=webp/51735/uploads/urunresimleri/buyuk/mad-draco-100-ml-unisex-parfum100-ml--461b-.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "dream lighet",
        "Image Link": "https://madperfume.co.il/upload/02-2025/product/mad-dreamlight-100-ml-kadin-parfumnich-da0c48.webp",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Effect",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/effect-100ml-unisex-parfum.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "EGO",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/EGO.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Exploration",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/diverse-exploration.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "FORZA",
        "Image Link": "https://static.ticimax.cloud/cdn-cgi/image/width=540,quality=85,format=webp/51735/uploads/urunresimleri/buyuk/forza-100-ml-erkek-parfum100-ml-b21-45.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Gold Intens",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/WhatsApp Image 2023-06-30 at 01.06.24.jpeg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Golden Age",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/mad-golden-age-100-ml-kadin-parfum100--0ae4a4.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Golden Feel",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/mad-golden-feel-.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Golden Glory",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/mad-golden-glory-100-ml-kadin-parfum10-26-4f6.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Golden Soul",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/mad-golden-soul-.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Grande Notte",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/grande-notte.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Gumin",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/gumen.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Hot Passion",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/hot-passion-.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Inspiraiton",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/inspiration.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Inviting",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/inviting.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Lady",
        "Image Link": "https://madperfume.co.il/upload/09-2024/product/WhatsApp Image 2024-09-19 at 13.55.53.jpeg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Love me",
        "Image Link": "https://madperfume.co.il/upload/03-2025/product/I-278.png",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Mad Absolutely",
        "Image Link": "https://madperfume.co.il/upload/07-2024/product/668baff8aa2a2.png",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "mad man",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/MAN.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Mad Midnight 100 ml Unisex",
        "Image Link": "https://madperfume.co.il/upload/11-2024/product/mad-midnight-100-ml-unisex-parfum100-m-ca4a-5.webp",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Madam",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/mad-madam.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Madam Amour",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/madam.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Madam The Roman Night",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/madam-the-roman-night-100ml-kadin-parf-4732-8.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "MALIK",
        "Image Link": "https://madperfume.co.il/upload/04-2024/product/660c3921be565.png",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Mare",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/mad-mare-50-ml-erkek-parfum50ml-f73-1a.jpeg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Monalisa",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/monalisa.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Narcotic ",
        "Image Link": "https://static.ticimax.cloud/cdn-cgi/image/width=540,quality=85,format=webp/51735/uploads/urunresimleri/buyuk/mad-narcotic-100-ml-unisex-parfum100-m--4c09-.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Narcotic Intense 100 ml",
        "Image Link": "https://madperfume.co.il/upload/03-2024/product/mad-narcotic-intense-100-ml-erkek-parf-633af8.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "NEW YORK",
        "Image Link": "https://static.ticimax.cloud/cdn-cgi/image/width=540,quality=85,format=webp/51735/uploads/urunresimleri/buyuk/mad-new-york-night-100-ml-kadin-parfum-2-a445.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "NO47",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/47.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "OMBRE",
        "Image Link": "https://madperfume.co.il/upload/09-2024/product/66ec7c0f70353.jpeg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Opus",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/WhatsApp Image 2023-06-30 at 01.02.55.jpeg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Oud 01",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/o-101-malaki-oud.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Oud 02",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/o-102-sateen-oud.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Oud 03",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/o-103-wonderwood-oud.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Oud Supreme",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/mad-oud-supreme-100-ml-erkek-parfum100--478d-.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "PERA",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/WhatsApp Image 2023-06-30 at 13.47.45.jpeg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Prevail",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/prevail.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Rouge Empreisa 100 ml Unisex Parfüm",
        "Image Link": "https://madperfume.co.il/upload/07-2024/product/668ba4fe4713b.png",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Rouge night",
        "Image Link": "https://madperfume.co.il/upload/12-2023/product/6578b3066565c.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Sapphire",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/mad-sapphire-100-ml-unisex-parfum100-m-28f-70.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "SEA LIGHET",
        "Image Link": "https://madperfume.co.il/upload/03-2024/product/6603fb5a926da.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Secret Night",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/secret-night-100ml-kadin-parfum-3-86c7.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Sense",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/sense-100ml-kadin-parfum-4088-e.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "STARLIGHET",
        "Image Link": "https://madperfume.co.il/upload/02-2025/product/mad-starlight-100-ml-kadin-parfum100-m-e-9b11.webp",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Sweet Bouquet",
        "Image Link": "https://madperfume.co.il/upload/07-2024/product/668bb3761f651.png",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Trono",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/trono.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "-Mad-Berry-Endless-120-ML",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/mad-berry-endless-120ml-ortam-kokusu-7c9bea.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Mad Fruit Fusion",
        "Image Link": "https://static.ticimax.cloud/cdn-cgi/image/width=615,quality=85,format=webp/51735/uploads/urunresimleri/buyuk/mad-fruit-fusion-120-ml-ortam-kokusu-99b79-.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "-Mad-Bosphorus-120-ML",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/mad-bosphorus-120-ml-ortam-kokusu120-m-433ad1.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "-MAd-Bright-Citrus-120-ML",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/mad-bright-citrus-120ml-ortam-kokusu-7-5435.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "-Mad-Dream-Buquet-120-ML",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/mad-dream-bouquet-120ml-ortam-kokusu--96658.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "-Mad-Fresh-Bloom-120-ML-",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/mad-fresh-bloom-120ml-ortam-kokusu--472f-.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "-Mad-Green-Earth-120-ML",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/mad-green-earth-120-ml-ortam-kokusu120-81ba10.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "-Mad-Hypnotizya-120-ML",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/mad-hipnotizya-120ml-ortam-kokusu-eac1-b.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "-Mad-Limpio-120-ML",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/mad-limpio-120-ml-ortam-kokusu120-ml-a646-b.jpeg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "-Mad-Strong-Stick-120-ML",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/mad-strong-stick-120ml-ortam-kokusu-1b9044.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "authentic",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/mad-authentic-120ml-ortam-kokusu-9b27-8.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Deep-Impression-120-ML",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/mad-deep-impressi-120ml-ortam-kokusu-29b399.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Good-Night-Kiss-120-ML-",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/mad-good-night-kiss-120-ml-ortam-kokus-0fe9c0.jpeg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Mad-Mona-Rosa-120-ML",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/mad-mona-rosa-120ml-ortam-kokusu-8b-475.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Pretty-Sweet-120-ML-",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/mad-pretty-sweet-120ml-ortam-kokusu-d7a2e7.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Pure-Natural-120-ML",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/mad-pure-naturel-120ml-ortam-kokusu--674b-.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Purple Night",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/mad-purple-night-120ml-ortam-kokusu-3f25-f.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Summer Dream 120 ML",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/mad-summer-dream-120ml-ortam-kokusu-2a-581.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Tropic-Wind-120-ML",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/mad-tropic-wind-120ml-ortam-kokusu-3d-265.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "turkish bath",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/mad-turkish-bath-120-ml-ortam-kokusu12-2da8a8.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "COOFFE",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/mad-coffee-biscuit-200-gr-mum-b6d1-0.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "halloween",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/mad-halloween-200-gr-mum--b7a-48.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Mad-Sunshine",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/mad-sunshine-200-gr-mum--fe-a9a.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Prevail",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/mad-prevail-200-gr-mum--6-b2f8.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Wizard",
        "Image Link": "https://madperfume.co.il/upload/09-2023/product/mad-wizard-200-gr-mum--332160.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "VANILLA CARNIVAL",
        "Image Link": "https://static.ticimax.cloud/cdn-cgi/image/width=615,quality=85,format=webp/51735/uploads/urunresimleri/buyuk/mad-vanilla-carnaval-200-gr-mum200-gr--fdbb-.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "SPICY APPLE",
        "Image Link": "https://static.ticimax.cloud/cdn-cgi/image/width=615,quality=85,format=webp/51735/uploads/urunresimleri/buyuk/mad-spicy-apple-200-gr-mum200-gr-3e3-ad.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "AUTUMN WIND",
        "Image Link": "https://drive.google.com/file/d/1iakksiTi81WL0c3SQqeFf9Ki0-hD8HtO/view",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "SPRING",
        "Image Link": "https://drive.google.com/file/d/1iakksiTi81WL0c3SQqeFf9Ki0-hD8HtO/view",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "WINTER TALE",
        "Image Link": "https://static.ticimax.cloud/cdn-cgi/image/width=615,quality=85,format=webp/51735/uploads/urunresimleri/buyuk/mad-sunshine-200-gr-mum-cam-bardak200--b7c-19.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "WIZARD",
        "Image Link": "https://static.ticimax.cloud/cdn-cgi/image/width=615,quality=85,format=webp/51735/uploads/urunresimleri/buyuk/mad-wizard-200-gr-mum-cam-bardak200-gr-b-48e1.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Mad Rouge Night",
        "Image Link": "https://static.ticimax.cloud/cdn-cgi/image/width=615,quality=85,format=webp/51735/uploads/urunresimleri/buyuk/mad-rouge-night-200-gr-mum-cam-bardak2-bcb9ac.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Mad Prevail",
        "Image Link": "https://static.ticimax.cloud/cdn-cgi/image/width=615,quality=85,format=webp/51735/uploads/urunresimleri/buyuk/mad-prevail-200-gr-mum-cam-bardak200-g-453-a7.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "\\r\\nMad Narcotic ",
        "Image Link": "https://static.ticimax.cloud/cdn-cgi/image/width=615,quality=85,format=webp/51735/uploads/urunresimleri/buyuk/mad-narcotic-200-gr-mum-cam-bardak200--d-a326.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "COFFEE BISQUIT",
        "Image Link": "https://static.ticimax.cloud/cdn-cgi/image/width=615,quality=85,format=webp/51735/uploads/urunresimleri/buyuk/mad-coffee-biscuit-200-gr-mum-cam-bard-cae02a.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Favorilere Ekle Mad Hipnotizya 500 ml",
        "Image Link": "https://madperfume.co.il/upload/12-2023/product/IMG_8808.jpeg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Favorilere Ekle Mad Mona Rosa 500 ml",
        "Image Link": "https://madperfume.co.il/upload/12-2023/product/IMG_8813.jpeg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Favorilere Ekle Mad Pure Natural 500 ml",
        "Image Link": "https://madperfume.co.il/upload/12-2023/product/IMG_8812.jpeg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Mad Dream Bouquet 500 ml",
        "Image Link": "https://madperfume.co.il/upload/12-2023/product/IMG_8814.jpeg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Mad Rain Forest 500 ml",
        "Image Link": "https://madperfume.co.il/upload/12-2023/product/IMG_8811.jpeg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Mad Turkish Bath 500 ml",
        "Image Link": "https://madperfume.co.il/upload/12-2023/product/IMG_8806.jpeg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "בושם לרכב מיקס",
        "Image Link": "https://madperfume.co.il/upload/12-2023/product/mad-karpuz-cilek-8-ml-arac-kokusu8-ml--4076-.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "gift",
        "Image Link": "https://madperfume.co.il/upload/12-2023/product/mad-brave-selection-160-ml-sac-parfumu-15-b95.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Mad Passion Fruit",
        "Image Link": "https://madperfume.co.il/upload/12-2023/product/mad-passion-fruit-160-ml-sac-parfumu16-02b382.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Mad Peerles Delight  ",
        "Image Link": "https://madperfume.co.il/upload/12-2023/product/mad-peerles-delight-160-ml-sac-parfumu-1-e358.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Mad Pretty Beauty ",
        "Image Link": "https://madperfume.co.il/upload/12-2023/product/mad-pretty-beauty-160-ml-sac-parfumu16-0-7b24.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Mad Amber 110 ml Kolonya",
        "Image Link": "https://madperfume.co.il/upload/08-2024/product/66b8776a01623.png",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "gift",
        "Image Link": "https://madperfume.co.il/upload/08-2024/product/66b8769de0b09.png",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "gift",
        "Image Link": "https://madperfume.co.il/upload/08-2024/product/66b8766dac4fa.png",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "gift",
        "Image Link": "https://madperfume.co.il/upload/08-2024/product/66b87633c78c1.png",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "gift",
        "Image Link": "https://madperfume.co.il/upload/08-2024/product/66b8774cdd757.png",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "gift",
        "Image Link": "https://madperfume.co.il/upload/08-2024/product/66b876bda449c.png",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "gift",
        "Image Link": "https://madperfume.co.il/upload/08-2024/product/66b876ecda2b8.png",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "gift",
        "Image Link": "https://madperfume.co.il/upload/08-2024/product/66b875f09d0a7.png",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "gift",
        "Image Link": "https://madperfume.co.il/upload/08-2024/product/66b8773361469.png",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "gift",
        "Image Link": "https://madperfume.co.il/upload/08-2024/product/66b87653c3691.png",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "gift",
        "Image Link": "https://madperfume.co.il/upload/08-2024/product/66b87714215df.png",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "gift",
        "Image Link": "https://madperfume.co.il/upload/08-2024/product/66b87a0a00f1b.png",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Mad Aqua Di Blue 200 ml Kolonya",
        "Image Link": "https://madperfume.co.il/upload/08-2024/product/66b879312000a.png",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Mad Bergamot 200 ml Kolonya",
        "Image Link": "https://madperfume.co.il/upload/08-2024/product/66b8785b61af3.png",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Mad Bodrum Tangerine 200 ml Kolonya",
        "Image Link": "https://madperfume.co.il/upload/08-2024/product/66b878ff21b89.png",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Mad Dream Bouquet 200 ml Kolonya",
        "Image Link": "https://madperfume.co.il/upload/08-2024/product/66b879962d989.png",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Mad Fig Desert 200 ml Kolonya",
        "Image Link": "https://madperfume.co.il/upload/08-2024/product/66b878c63ad2b.png",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Mad Green Tea 200 ml Kolonya",
        "Image Link": "https://madperfume.co.il/upload/08-2024/product/66b877e67868f.png",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Mad Ice 200 ml Kolonya",
        "Image Link": "https://madperfume.co.il/upload/08-2024/product/66b8783658611.png",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Mad Japanese Cherry Blossom 200 ml Kolonya",
        "Image Link": "https://madperfume.co.il/upload/08-2024/product/66b87a37e5a21.png",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Mad Lavender 200 ml Kolonya",
        "Image Link": "https://madperfume.co.il/upload/08-2024/product/66b878a2ad2a4.png",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Mad Lime 200 ml Kolonya",
        "Image Link": "https://madperfume.co.il/upload/08-2024/product/66b877c25cb70.png",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Mad Mimosa 200 ml Kolonya",
        "Image Link": "https://madperfume.co.il/upload/08-2024/product/66b8795e90a41.png",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Mad Neroli 200 ml Kolonya",
        "Image Link": "https://madperfume.co.il/upload/08-2024/product/66b8780f3b543.png",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Mad Velvet Lavender 200 ml Kolonya",
        "Image Link": "https://madperfume.co.il/upload/08-2024/product/66b8779f07e39.png",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "SWEET BEACH",
        "Image Link": "https://madperfume.co.il/upload/09-2024/product/66e69893991c7.png",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "SUN KISS",
        "Image Link": "https://madperfume.co.il/upload/09-2024/product/66e6aa95a1820.png",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "CHARM",
        "Image Link": "https://madperfume.co.il/upload/09-2024/product/66e6a6e97dc76.png",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "COCONUT SHINR",
        "Image Link": "https://madperfume.co.il/upload/09-2024/product/66e6a5ca2b4f3.png",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "VANILLA SKY",
        "Image Link": "https://madperfume.co.il/upload/09-2024/product/66e6a550c2789.png",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "SEA MIST",
        "Image Link": "https://madperfume.co.il/upload/09-2024/product/66e6a5029fc32.png",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "DAYFREAM",
        "Image Link": "https://madperfume.co.il/upload/09-2024/product/66e6a3ce0b411.png",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "SIVI SABUN  MAD VELVET LAVENDER 250ml",
        "Image Link": "https://madperfume.co.il/upload/10-2024/product/670f80455d060.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "Sify Soap Mad Ice 250ml",
        "Image Link": "https://madperfume.co.il/upload/10-2024/product/670f806f7bb56.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "SIVI SABUN   MAD JAPANESE CHERRY  BLOSSOM 250ml",
        "Image Link": "https://madperfume.co.il/upload/10-2024/product/670f80b392f1d.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "SIVI SABUN   MAD AMBER250ml",
        "Image Link": "https://madperfume.co.il/upload/10-2024/product/670f80ef78414.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "RAIN FORREST",
        "Image Link": "https://static.ticimax.cloud/cdn-cgi/image/width=615,quality=85,format=webp/51735/uploads/urunresimleri/buyuk/mad-rain-forest-250-ml-luks-oda-spreyi-338-d0.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "MONA ROSA",
        "Image Link": "https://static.ticimax.cloud/cdn-cgi/image/width=615,quality=85,format=webp/51735/uploads/urunresimleri/buyuk/mad-mona-rosa-250-ml-luks-oda-spreyi25-2-185c.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "TURKISH BATH",
        "Image Link": "https://static.ticimax.cloud/cdn-cgi/image/width=615,quality=85,format=webp/51735/uploads/urunresimleri/buyuk/mad-turkish-bath-250-ml-luks-oda-sprey-acdd-9.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "DEREAM BOUQET",
        "Image Link": "https://static.ticimax.cloud/cdn-cgi/image/width=615,quality=85,format=webp/51735/uploads/urunresimleri/buyuk/mad-dream-bouquet-250-ml-luks-oda-spre-3d8abc.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "PURE NATURAL",
        "Image Link": "https://static.ticimax.cloud/cdn-cgi/image/width=615,quality=85,format=webp/51735/uploads/urunresimleri/buyuk/mad-pure-natural-250-ml-luks-oda-sprey-86f4b5.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "HIPONYTZYA",
        "Image Link": "https://static.ticimax.cloud/cdn-cgi/image/width=615,quality=85,format=webp/51735/uploads/urunresimleri/buyuk/mad-hipnotizya-250-ml-luks-oda-spreyi2-78c183.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "PREVIL 160ML",
        "Image Link": "https://static.ticimax.cloud/cdn-cgi/image/width=615,quality=85,format=webp/51735/uploads/urunresimleri/buyuk/mad-prevail-160-ml-ortam-kokusu160-ml-7f3-86.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "NARCOTIC 160ML",
        "Image Link": "https://static.ticimax.cloud/cdn-cgi/image/width=615,quality=85,format=webp/51735/uploads/urunresimleri/buyuk/mad-narcotic-160-ml-ortam-kokusu160-ml-b87adc.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "COFFE BISCUIT",
        "Image Link": "https://static.ticimax.cloud/cdn-cgi/image/width=615,quality=85,format=webp/51735/uploads/urunresimleri/buyuk/mad-coffee-biscuit-160-ml-ortam-kokusu-48ce-9.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "ROUGH NIGHT 160 ML",
        "Image Link": "https://static.ticimax.cloud/cdn-cgi/image/width=615,quality=85,format=webp/51735/uploads/urunresimleri/buyuk/mad-rouge-night-160-ml-ortam-kokusu160--ae0c-.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "WIZARD",
        "Image Link": "https://d3m9l0v76dty0.cloudfront.net/system/logos/6576/original/e6744af4e8ed5604198ee0b91a48f26e.png",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "SUN SHINE",
        "Image Link": "https://static.ticimax.cloud/cdn-cgi/image/width=318,quality=85,format=webp/51735/uploads/urunresimleri/buyuk/mad-sunshine-160-ml-ortam-kokusu160-ml-baa3-d.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "VANILLA CARNAVAL",
        "Image Link": "https://static.ticimax.cloud/cdn-cgi/image/width=615,quality=85,format=webp/51735/uploads/urunresimleri/buyuk/mad-vanilla-carnaval-160-ml-ortam-koku-b3-e07.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "CP.5.BLACK REFIL",
        "Image Link": "https://static.ticimax.cloud/cdn-cgi/image/width=615,quality=85,format=webp/51735/uploads/urunresimleri/buyuk/mad-doldurulabilir-5-ml-black-cep-parf-4ed-7d.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "CP.5.SILVER REFIL",
        "Image Link": "https://static.ticimax.cloud/cdn-cgi/image/width=615,quality=85,format=webp/51735/uploads/urunresimleri/buyuk/mad-doldurulabilir-5-ml-silver-cep-par-014541.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "CP.5.RED REFIL",
        "Image Link": "https://static.ticimax.cloud/cdn-cgi/image/width=615,quality=85,format=webp/51735/uploads/urunresimleri/buyuk/mad-doldurulabilir-5-ml-red-cep-parfum-be5864.jpg",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "tseter",
        "Image Link": "https://encrypted-tbn2.gstatic.com/shopping?q=tbn:ANd9GcRZ_4Cgzstpc6yo2Pzdl6hPBUlySqq053cGq_zxaZQrRFvhxeZO5qvtzY2auN6NINmc0N_Fl6jf_jlCN15bkptSsCisaS0ZXLhkJX9b87AlRmSwqeLDSWnrUDziWb8skk6OVVI9zA&usqp=CAc",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "key paprer חבילה",
        "Image Link": "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTdIEpNVKfGjTjUQdMSlz22JVgufQkQwziOJg&s",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "karton",
        "Image Link": "https://encrypted-tbn3.gstatic.com/shopping?q=tbn:ANd9GcSSnGiqiifzxtxGK0xcQi9NHHG7HfmxvlSki4R8rwrOEpG6csUsvDhgev1BaVqs6aycgTS_oeBBUfhalGq9qDqaRnZQ9hExhSRv-zjnwBdGr40_kR5-0BCHyfodIqT83zs931KsdrU&usqp=CAc",
        "Longitude": "34.5",
        "Latitude": "32.5"
    },
    {
        "ProductName": "karton",
        "Image Link": "https://encrypted-tbn3.gstatic.com/shopping?q=tbn:ANd9GcSSnGiqiifzxtxGK0xcQi9NHHG7HfmxvlSki4R8rwrOEpG6csUsvDhgev1BaVqs6aycgTS_oeBBUfhalGq9qDqaRnZQ9hExhSRv-zjnwBdGr40_kR5-0BCHyfodIqT83zs931KsdrU&usqp=CAc",
        "Longitude": "34.5",
        "Latitude": "32.5"
    }
]);
          const [searchQuery, setSearchQuery] = React.useState('');
          const [filteredProducts, setFilteredProducts] = React.useState(products);
          const [suggestions, setSuggestions] = React.useState([]);
          const [showSuggestions, setShowSuggestions] = React.useState(false);

          React.useEffect(() => {
            if (selectedProduct) {
              const interval = setInterval(() => {
                setProducts(prevProducts => prevProducts.map(product =>
                  product.ProductName === selectedProduct.ProductName ? { ...product, blinking: !product.blinking } : product
                ));
              }, 300);
              return () => clearInterval(interval);
            }
          }, [selectedProduct]);

          React.useEffect(() => {
            const results = products.filter(product =>
              product.ProductName.toLowerCase().includes(searchQuery.toLowerCase())
            );
            setFilteredProducts(results);

            if (searchQuery) {
              const suggestionResults = products
                .filter(product =>
                  product.ProductName.toLowerCase().startsWith(searchQuery.toLowerCase())
                )
                .slice(0, 5);
              setSuggestions(suggestionResults);
              setShowSuggestions(true);
            } else {
              setSuggestions([]);
              setShowSuggestions(false);
            }
          }, [searchQuery, products]);

          const handleInputChange = (event) => {
            setSearchQuery(event.target.value);
          };

          const handleSuggestionClick = (suggestion) => {
            setSearchQuery(suggestion.ProductName);
            setShowSuggestions(false);
          };

          const handleMouseDown = (product) => {
            setDraggingProduct(product);
            setIsDragging(true);
          };

          const handleMouseMove = (event) => {
            if (isDragging && draggingProduct) {
              const rect = event.target.closest('.relative').getBoundingClientRect();
              const x = ((event.clientX - rect.left) / rect.width) * 100;
              const y = ((event.clientY - rect.top) / rect.height) * 100;

              const updatedProducts = products.map(product =>
                product.ProductName === draggingProduct.ProductName ? { ...product, Longitude: x, Latitude: y } : product
              );

              setProducts(updatedProducts);
            }
          };

          const handleMouseUp = () => {
            setIsDragging(false);
            setDraggingProduct(null);
          };

          return (
            <div
              className="min-h-screen text-white p-0 bg-cover bg-center relative"
              style={{
                backgroundImage: 'url(https://images.unsplash.com/photo-1506748686214-e9df14d4d9d0)',
                backgroundSize: 'cover',
                backgroundPosition: 'center',
                width: '100%',
                height: '100vh',
                backgroundRepeat: 'no-repeat',
              }}
              onMouseMove={handleMouseMove}
              onMouseUp={handleMouseUp}
              onTouchMove={handleMouseMove}
              onTouchEnd={handleMouseUp}
            >
              <div className="absolute top-4 left-4 bg-white bg-opacity-75 rounded-md p-2 z-10">
                <input
                  type="text"
                  placeholder="ابحث عن منتج..."
                  className="text-black rounded-md p-2"
                  value={searchQuery}
                  onChange={handleInputChange}
                  onFocus={() => setShowSuggestions(searchQuery.length > 0)}
                  onBlur={() => setTimeout(() => setShowSuggestions(false), 200)}
                />
                {showSuggestions && suggestions.length > 0 && (
                  <ul className="absolute left-0 mt-1 bg-white border border-gray-300 rounded-md shadow-lg z-20">
                    {suggestions.map((suggestion, index) => (
                      <li
                        key={index}
                        className="text-black p-2 cursor-pointer hover:bg-gray-100"
                        onClick={() => handleSuggestionClick(suggestion)}
                      >
                        {suggestion.ProductName}
                      </li>
                    ))}
                  </ul>
                )}
              </div>

              {filteredProducts.map((product, index) => (
                <div
                  key={index}
                  className={`absolute cursor-pointer ${product.blinking ? 'animate-pulse' : ''}`}
                  style={{
                    top: `${product.Latitude}%`,
                    left: `${product.Longitude}%`
                  }}
                  onMouseDown={() => handleMouseDown(product)}
                  onTouchStart={() => handleMouseDown(product)}
                  onClick={() => setSelectedProduct(product)}
                >
                  {product["Image Link"] && (
                    <img src={product["Image Link"]} alt={product.ProductName} className="w-8 h-8 rounded-full border border-white" />
                  )}
                </div>
              ))}
            </div>
          );
        };

        const root = ReactDOM.createRoot(document.getElementById('root'));
        root.render(<WarehouseMap />);
    </script>
</body>
</html>
