<script>
    import {page} from '$app/stores'
    const productId=$page.params.productId
    const reviewId=$page.params.reviewId
</script>

<h1>
    This is {productId}'s review {reviewId}
</h1>