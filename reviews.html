<?php
// PHP logic to capture free text input, write to a file, and display as read-only.
$file = 'reviews_data.txt';

// Handle form submission
if ($_SERVER["REQUEST_METHOD"] == "POST" && !empty(trim($_POST["review_text"]))) {
    $new_review = htmlspecialchars(trim($_POST["review_text"]));
    $timestamp = date("Y-m-d H:i:s");
    $formatted_entry = "<div class='card' style='margin-bottom: 1rem;'><p>\"" . $new_review . "\"</p><small style='color: var(--secondary-gold);'>— Submitted on " . $timestamp . "</small></div>\n";
    
    // Append the new review to the file
    file_put_contents($file, $formatted_entry, FILE_APPEND | LOCK_EX);
    
    // Refresh to prevent duplicate form submission on reload
    header("Location: " . $_SERVER['REQUEST_URI']);
    exit();
}

// Read existing reviews
$existing_reviews = file_exists($file) ? file_get_contents($file) : "<p>No reviews yet. Be the first to leave one!</p>";
?>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tejada Construction LLC | Reviews</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="icon" type="image/x-icon" href="favicon.ico">
</head>
<body>
    <aside class="sidebar">
        <div class="brand-title">Tejada Const.</div>
        <nav>
            <a href="index.html">Home</a>
            <a href="services.html">Services</a>
            <a href="about.html">About Us</a>
            <a href="reviews.html" class="active">Reviews</a>
            <a href="contact.html">Contact</a>
        </nav>
    </aside>

    <main class="main-content">
        <h1>Client Testimonials</h1>
        <p>Leave a review about your experience with Tejada Construction LLC.</p>

        <form action="" method="POST" style="margin-bottom: 2rem;">
            <label for="review_text" style="color: var(--secondary-gold);">Write a Review</label>
            <textarea id="review_text" name="review_text" rows="4" placeholder="Share your experience..." required></textarea>
            <button type="submit">Submit Review</button>
        </form>

        <h2>Recent Reviews</h2>
        <div class="reviews-container">
            <!-- PHP outputs the read-only file content here -->
            <?php echo $existing_reviews; ?>
        </div>

        <footer style="margin-top: 3rem;">
            Site design by Harrison AI Agents.
        </footer>
    </main>
</body>
</html>
