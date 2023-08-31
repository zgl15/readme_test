## Code Examples

<div class="tab">
    <input type="checkbox" id="tab-python" class="tab-input">
    <label class="tab-label" for="tab-python">Python</label>
    <div class="tab-content">
        ```python
        # Your Python code here
        ```
    </div>
    
    <input type="checkbox" id="tab-r" class="tab-input">
    <label class="tab-label" for="tab-r">R</label>
    <div class="tab-content">
        ```r
        # Your R code here
        ```
    </div>
</div>

<style>
.tab {
    display: flex;
    flex-direction: column;
}

.tab-input {
    display: none;
}

.tab-label {
    padding: 8px 16px;
    background-color: #f1f1f1;
    border: 1px solid #ccc;
    cursor: pointer;
}

.tab-content {
    display: none;
    padding: 8px 16px;
    border-top: none;
}

.tab-input:checked + .tab-label + .tab-content {
    display: block;
}
</style>
