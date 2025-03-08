# Tugas_1

// 1. Menemukan luas persegi panjang
function areaOfRectangle(length, width) {
    return length * width;
}
console.log("Output: " + areaOfRectangle(5, 3)); // Output: 15


// 2. Menghitung diameter, keliling, dan luas lingkaran



// 3. Menemukan sudut segitiga jika dua sudut diberikan
function findTriangleAngle(a, b) {
    return 180 - (a + b);
}
console.log("Output: " + findTriangleAngle(80, 65)); // Output: 35


// 4. Menghitung selisih antara dua tanggal dalam hari
function dateDifference(date1, date2) {
    const diffTime = Math.abs(new Date(date2) - new Date(date1));
    return Math.ceil(diffTime / (1000 * 60 * 60 * 24)); // konversi ke hari
}
console.log("Output: " + dateDifference('2024-03-19', '2024-03-21')); // Output: 2


// 5. Mencetak inisial nama dalam huruf kapital
function nameInitials(name) {
    const initials = name.split(' ').map(word => word.charAt(0).toUpperCase()).join('');
    return initials;
}
console.log("Output: " + nameInitials("John Doe")); // Output: JD
